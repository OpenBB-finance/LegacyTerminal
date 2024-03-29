---
title: baas
description: This documentation is related to the 'baas' function which displays the
  average bid, ask prices, and spread for a chosen crypto pair over a specified time
  period. The function can work with various cryptocurrencies and ERC 20 tokens.
keywords:
- baas
- crypto pair
- average bid
- average ask prices
- spread
- time period
- ERC20 token
- crypto currency
- ETH
- USD
- BTC
- USDT
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="crypto/onchain/baas - Reference | OpenBB Terminal Docs" />

Display average bid, ask prices, spread for given crypto pair for chosen time period [Source: https://graphql.bitquery.io/]

### Usage

```python
baas [-c COIN] [-vs {ETH,USD,BTC,USDT}] [-l LIMIT] [-s {date,baseCurrency,quoteCurrency,dailySpread,averageBidPrice,averageAskPrice}] [-r]
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| coin | ERC20 token symbol or address. | None | True | WETH, USDC, USDT, DAI, WBTC, FEI, sUSD, SHIB, SUSHI, ETH, OHM, UNI, LINK, AAVE, renBTC, TUSD, -, sETH, YFI, imBTC, ALCX, TRIBE, HEX, BNT, SPELL, sBTC, BUSD, UST, CVX, KOKO, FRAX, ETH2x-FLI, LUSD, ELON, LEASH, RAI, MC, EDEN, DYDX, 1INCH, EURS, RBN, MKR, ENS, BIT, ILV, CRV, DELTA, SNX, TOKE, MATIC, SQUID, SYN, SAITAMA, COMP, AGLD, FODL, EURT, BONE, DOG, SAND, AMPL, FNK, PAX, BAC, BDP, DPI, MIC, FTM, TRU, BADGER, BAL, HBTC, AXS, FXS, LRC, MOCHI, WISE, UFO, eRSDL, ESD, sLINK, RGT, STARL, DYP, LOBI, DOE, PERP, TKING, PEOPLE, AKITA, BOND, WDOGE, VSP, MM, ICE, LDO, RARE, CENNZ, xSUSHI, BDI, GM, CARDS, DSD, FARM, MIR, KISHU, AMP, RPL, FLOKI, DIGG, MIS, NCR, YGG, cvxCRV, KINE, CEL, ENJ, LON, MANA, GNO, NU, DRC, BGLD, SHKOOBY, NFD, ALPHA, BAS, PICKLE, RLY, ibEUR, NFTX, FEG, GALA, WOO, welp, SCAMMY, generalize fix for rebass tokens, RAD, Ian Laphan fan token, KP3R, SUPER, ROOK, FLX, REN, MIM, PSP, POLS, agEUR, BANK, NEXO, CORE, sETH2, FLOOR, RUNE, VISR, MCB, UNQT, IMX, BMI, LYXe, STRONG, REB, HGT, UMA, KUMA, BOTTO, WTON, BAND, DAO, AUDIO, XOR, SOUL, bALPHA, TORN, GRO, LEND, ERN, XXi, GYEN, DEXTF, INST, CREAM, VEMP, GRPFT, aKLIMA, ZCX, ibBTC, wNXM, USE, FTX Token, VADER, PLUG, PILOT, stETH, WOOL, KEEP, eXRD, ANY, TUBE2, VERSE, 10SET, DODO, STMX, STAKE, FOX, WAXE, GRT, EVN, RACA, COLLAR, KBTC, XSGD, yveCRV-DAO, aEth, LUNA, PUNK, DFX, LQTY, DERC, SHEESHA, SNGJ, ORB, LCX, BRAIN, RC_WETH_750_DAI_2021_3_31, OUSD, CHAIN, FX, SRM, SAK3, LIMIT, QNT, eMax, mIAU, CRO, USDN, HOPR, XMT, wCRES, 3Crv, EPAY, MASK, UFODOGE, $BASED, TTX, YAXIS, HOKK, PPAY, CAPY, DEA, RC_WBTC_25000_DAI_2021_3_31, OCEAN, DEUS, MILF, STA, pBTC, ibGBP, LPOOL, UBOMB, VRA, UNIX, MXS, LMT, LGB, COR, wPE, GERO, DFL, ZKS, DPX, KIMCHI, vBNT, DORA, Metis, PAID, yvBOOST, wstETH, KYL, BFC, NII, COC, BLACKHOLE, HANU, COTI, BEAN, DEV, LESS, sILV, sOHM, PEBBLE, KIRO, XES, Auction, ORN, GUSD, gm, SWAP, REQ, AUSCM, MPL, PAR, XTK, xSNXa, UMX, RBC, WGMI, OPUL, DEXT, uJENNY, HXB, PENDLE, COVER, ArtDeco, mFloki, TEL, KCAL, FREN, MetaCat, vETH, NAUSICAA, GTC, FREE, AXN, BANANA, SALE, AST1, PKF, BLOCKS, AST, BCS, 3DOG, SI, XFOC, BSOCIAL, MTA, BAT, YAM, UOS, $DG, COMBO, DEFI5, WHALE, APY, BOOST, WOOFY, SDT, YUAN, XEND, OGN, RAMP, yyDAI+yUSDC+yUSDT+yTUSD, LEAFA, SHAMAN, NTVRK, LONDON, buidl, SANSHU, SLP, CERTI, PAXG, LYM, eCum, SMINU, MIMO, UNISTAKE, ALBT, mLOOT, SHB5, GPYX, NOS, RKYU, CTX, K9, CZ, C3, 3TH, CHARLOTTE, COIN, PNT, JEJUDOGE, GMGN, ROOM, FEWGO, SKL, MCO2, BONDLY, GDT, XCAD, BNS, FGLD, XFIT, IDTT, EFI, DOGEGF, HUMAN, XP, Eevee Inu , MEME, PLUG-B, LIX, VXV, OCC, DVF, UBT, YAMv2, pBTC35A, GMT, CUBE, MCC, HEZ, DRF, PUSH, TEMP, RAIL, yDAI+yUSDC+yUSDT+yTUSD, AION, PREMIA, Lelouch, DBUY, XAUt, QRDO, wANATHA, TCAP, BEZOGE, SYLO, STAK, RUSD, oneUNI, PSHIB, xAAVEb, SBC DAO, ID, FOMO, SCREAMINU, SqINU, XYO, XTM, WAGMI, STARB, ViCA, DAM, ANGLE, AIOZ, USF, FST, MFG, SOCRAT, BTRST, PAPER, CONV, POLK, SAFE, 69, RVST, WING, CHINU, MSHIBA, GIZMO, COPE, OOP, MTO, METAGOKU, BLACKSTALLION, AKITACASH, Interstellar, RFOX, NBNG, DIADOGE, APED, BTC2x-FLI, HZM, TECH, MOON, pLTC, MPY, WOGE, FLOAT, SHFL, CAKEINU, LEBRON, RSR, RARI, WXT, RULER, ODA, VLT, PKINU, ERC20, MFS, WWT, VOL, HINU, YLD, PICIPO, GNBU, SWAG, TFI-LP, METACEX, ASTRO, OPM, LEECH, Yf-DAI, SHINU, HOUND, LBY, AFT, ANIME, rDPX, RAICHU, DGCL, SPANK, CHININU, MGC, ICHI, ZENDOGE, KOMBAT, KISHIMOTO, LEEEEECH, SAPINU, SPIDEYINU  , ELAND, SCOOP, DONI, SDOG, ZINU, GIVE, SUPER HEAVY , LGBTSHIBA, SHIB2, CIAO, BARK, TOKYOGHOUL, AVINOC, BIN, BID, TMTG, MLINK, NFY, VAMINU, GG, ORION, WASABI, GP, ROLL?, vETH2, CELL, TINYSAITAMA, 1Punch, RAC, MACROHARD, SGT, ODI, SCOOBY, Mononoke-Inu, CLAKE, SAT, TRND, NEWINU, KST, Rainbows, EWTB, SMT, DNXC, PMON, HMF, UBI, SER, MASHIMA, STIMMY, NFTD, GMI, xHDX, SAITO, MINT, YOP, UMB, LID, SPI, wsOHM, wCFG, GN, B20, XDEFI, MATTER, FDT, LBXC, ONX, SDL, FUN, DDOS, CC10, CoShi, LGCY, PXT, MTHD, ENCORE, TCR, mUSD, K21, ibETH, FNX, REVV, BULK, TOWN, SFI, LAYER, DOGE, ITS, TVK, TGX, Hi, WILD, CFi |
| vs | Quote currency | USDT | True | ETH, USD, BTC, USDT |
| limit | Number of days to display data for. | 10 | True | None |
| sortby | Sort by given column. | date | True | date, baseCurrency, quoteCurrency, dailySpread, averageBidPrice, averageAskPrice |
| reverse | Data is sorted in descending order by default. Reverse flag will sort it in an ascending way. Only works when raw data is displayed. | False | True | None |

---
