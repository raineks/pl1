# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?origin=place_id:ChIJw41iuB311YkREso8L-O3FfM&destination=place_id:ChIJ7TLxxjb_Lk0R-Iych7jVjWY&waypoints=place_id:ChIJKdlP2Pu8KogRHNWlrr2rbxk%7Cplace_id:ChIJfxc7Sre7Lk0RoOAk9nn7s30&avoid=tolls&mode=driving&alternatives=true&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE

```
## PlaceId's on Google Maps
```
https://www.google.com/maps/place/?q=place_id:ChIJw41iuB311YkREso8L-O3FfM
https://www.google.com/maps/place/?q=place_id:ChIJ7TLxxjb_Lk0R-Iych7jVjWY

https://www.google.com/maps/place/?q=place_id:ChIJKdlP2Pu8KogRHNWlrr2rbxk
https://www.google.com/maps/place/?q=place_id:ChIJfxc7Sre7Lk0RoOAk9nn7s30
```

## Next paste the full JSON response to this query here:

```
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJw41iuB311YkREso8L-O3FfM",
         "types" : [ "establishment", "point_of_interest", "university" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJKdlP2Pu8KogRHNWlrr2rbxk",
         "types" : [
            "convenience_store",
            "establishment",
            "food",
            "gas_station",
            "point_of_interest",
            "store"
         ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJfxc7Sre7Lk0RoOAk9nn7s30",
         "types" : [ "establishment", "point_of_interest", "store" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ7TLxxjb_Lk0R-Iych7jVjWY",
         "types" : [ "locality", "political" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 46.49318539999999,
               "lng" : -78.2818817
            },
            "southwest" : {
               "lat" : 43.7174424,
               "lng" : -81.0018467
            }
         },
         "copyrights" : "Map data ©2022 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "215 km",
                  "value" : 215280
               },
               "duration" : {
                  "text" : "2 hours 8 mins",
                  "value" : 7687
               },
               "end_address" : "201 Fairview Rd, Barrie, ON L4N 9B1, Canada",
               "end_location" : {
                  "lat" : 44.3519563,
                  "lng" : -79.6877009
               },
               "start_address" : "1600 W Bank Dr, Peterborough, ON K9L 0G2, Canada",
               "start_location" : {
                  "lat" : 44.3580479,
                  "lng" : -78.28912299999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 915
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 66
                     },
                     "end_location" : {
                        "lat" : 44.3503444,
                        "lng" : -78.2906617
                     },
                     "html_instructions" : "Head \u003cb\u003esoutheast\u003c/b\u003e on \u003cb\u003eNassau Mills Rd\u003c/b\u003e toward \u003cb\u003ePioneer Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ytvmG~yy|MJKZYh@U`@C@?b@BJ@|@L~Aj@B?DBTJlAl@LFRLnBjAl@d@fBtAzAx@|@`@n@Xv@LLBTAZA~@Qj@Q\\Qj@W|@[`@ORG`@INAHAZ@ZBXDXJVJ"
                     },
                     "start_location" : {
                        "lat" : 44.3580479,
                        "lng" : -78.28912299999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.4 km",
                        "value" : 2369
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 158
                     },
                     "end_location" : {
                        "lat" : 44.3305235,
                        "lng" : -78.2803739
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eUniversity Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sdumGrcz|MFm@Po@Zm@RSTQJG\\Q`@Qb@STIJE`@Of@QdBq@|Aq@`C_ArAg@z@[`@O`@MDAZMdA]`@ODCp@WDAp@YJCTKJELEFCJETKl@UTKJENIDAJETIBAFCTIJCxAi@JETIJETIJCTIJENGDAJEv@[l@UTILExAk@JCv@[d@Q`@QRILEdBo@?A`@MrAi@vBw@LGxAk@^O`@O`@Q`Aa@PGNG`@Of@QrAg@JGbAa@bAa@p@YtAi@`@Q`@O`@Q`@ORILEdBo@bA_@p@WPG`Cy@DC`@Mb@Q`@ODCr@WHCdCiA"
                     },
                     "start_location" : {
                        "lat" : 44.3503444,
                        "lng" : -78.2906617
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1427
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 102
                     },
                     "end_location" : {
                        "lat" : 44.3223186,
                        "lng" : -78.29323719999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWarsaw Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCounty Rd 4\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow County Rd 4\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "whqmGhcx|Mv@lAh@p@FFbBnBpClCtBrBtChCx@r@\\\\\\\\ZZ\\\\pCnCtBrBzBhC`@b@l@z@b@j@x@zANh@FRLv@zBlOt@fFZjBd@pC"
                     },
                     "start_location" : {
                        "lat" : 44.3305235,
                        "lng" : -78.2803739
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.3 km",
                        "value" : 3315
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 194
                     },
                     "end_location" : {
                        "lat" : 44.2939567,
                        "lng" : -78.28306529999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eTelevision Rd\u003c/b\u003e (signs for \u003cb\u003eCounty Road 35\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTelevision Road\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ouomGvsz|Mx@]bAa@^OlBw@~@_@rAi@x@[dCcAHE~@a@TMlAg@lGkCtAm@rAc@xDqAtEaBxAi@l@SzCeANEzBy@JEvDqAlAc@z@YfC_Ap@U|DwAdBm@dBo@zGcCzIyCpGyBb@On@Wr@WzAi@l@U`Aa@dBq@tCgA~EoBBAdA]\\I@?\\EXCrABr@Jb@LtAh@@?lDnA|@Xx@Tr@T`ADdABD@fAB"
                     },
                     "start_location" : {
                        "lat" : 44.3223186,
                        "lng" : -78.29323719999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "57.2 km",
                        "value" : 57192
                     },
                     "duration" : {
                        "text" : "33 mins",
                        "value" : 1983
                     },
                     "end_location" : {
                        "lat" : 43.9054239,
                        "lng" : -78.622894
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eHwy 7\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-115 S\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow ON-115 S\u003c/div\u003e",
                     "polyline" : {
                        "points" : "gdjmGdtx|M`@@RBXBNBLFVJRLNNRRRVFD@BzDlEJJPPtFhGrAzA~@dABBr@v@|@`A^b@bBjBNPZ^LLLNJL~BlCd@h@t@x@rAzA`@d@LNLLzAbBlAtAZ^HH`@b@Z\\v@|@~@fAh@j@FFpAxADFZ\\t@z@FHTV\\^VZhAnAX\\zDfE`CnCXZrB|Bv@|@d@j@Z\\LNHJLN`@f@^h@RVJPZf@Xd@NXR`@DHBBBHHPBDJPTh@LZVn@N`@BFJZBF@@Tt@HTNj@DHLj@DJH`@@DDPBJX|AVxAV`Bj@~DJl@`@nC@J?BJp@t@lFBJd@~CNjADVPpAb@|CXlBXrBTxA`@rC@Dv@tF|@hGv@xFbAbHdAlHt@rFh@jDl@~D`@vCf@nDZtBZ|BDXJn@b@bDL~@l@|D^nC`AzGlApI|G~e@x@tFl@nEz@zFHn@L|@Jn@DTNhA`@lCj@lDN~@@Hf@xB@DV|@n@nB\\v@@FNXLVr@pARZX`@^j@n@v@h@h@h@h@n@h@f@\\t@b@B@PHp@^ZN\\L|@^jBt@dA^rMtE~@\\`Bj@h@R`@LnL`ERHd@Pf@PVJ|@Zb@JjCbAnCnAPHRJf@Xx@b@RLRLZRFDj@\\f@\\dAv@t@h@jAbAdA`A^\\DDb@b@z@~@nAxAPRHJJJbArAd@p@`@j@~@vA@@b@p@lDjFtBbD~A`C`AvA`@n@d@t@RXfBlCvD|FhEpGjAdBr@hA`CnD~PrWfJjNX`@vAzBhDfFxCrEV^X`@Xb@rDtFdHnKfDfFdBjCjHxK|@rAbA|AlAjBX`@p@dAlAhBh@x@RXh@v@jExGXb@X`@T\\lC`EDHXb@\\j@t@tAJPDHZn@L\\^z@Vp@J\\HTJZRn@@DFRHV?@J\\HZH\\\\xA@?Ll@Nj@ZpANl@?@Pp@Lj@^xA?B`@|AJd@R|@h@vB@BPt@v@bDBFjAbFbA~DH`@lCxKH^`@|Af@tBb@hB~@zDnAfFvAbGnBhIdCdKT|@\\xAXhAd@jBbEzPDN|@rDLl@HZt@vChEjQLl@vA~FrMli@VfA`Qps@lBbIb@bB`@bB\\pADTHXNf@d@zAVp@Tp@JXLX|@pB\\r@Zl@j@`A\\j@V\\d@r@\\b@JNf@l@HHp@v@v@t@p@p@xCfChA`At@n@b@^zApAlAdABBXTt@p@PNVRf@b@HHPNb@^b@^fMtKb@`@VR\\ZXTd@b@|@t@z@t@zAnAxApAzDdDDD`@^HF`@\\@@bBxARNrCdCv@p@bBvApEzDf@d@~@t@nBbB`BvA\\Xl@h@z@t@hA`AdA|@jA`AxApAdBxARPb@^nAfAnHlGZX@@b@^nDzC\\Z\\Xf@b@\\Z\\X^Z\\Xz@t@`Az@dA|@^ZVVr@j@hB|AxBhBt@p@DBNLdA|@b@^^\\t@n@BBRPHFx@p@d@\\ZXb@\\l@`@~AbAv@d@p@^l@\\xBhAnBbAvC|AxC~Ah@XhCrAx@b@bB|@lAp@d@Vz@d@z@b@d@Xf@\\b@ZB@h@b@j@b@h@d@r@r@b@d@rAxAhE`FjKnLxFpGfCrClB|BpAzAlAzAf@p@X`@t@dAr@`AJNNRhCvDbA|AZb@fD`FdCpDjDhFRX?B@?@BLPDDXb@xEdHf@t@|@rAnBtCrApB|BhD^j@`@l@hHnK~CvEt@dAh@x@rCfEFHvDvFb@p@nEvGPXfCvDbEdGlGlJlAdBj@|@\\n@bAbBnA|BbAvBnArCj@xARh@N\\pKlYRh@FPJVRj@p@fBf@rAf@rAz@zB@BRh@tArD`CrGRj@^bAFLlAdDz@|BnBjFn@`BbBtEtBtFz@|BBHRf@N^Ph@@?dD~Iv@tBv@rBRh@p@fB^bA`@`Ab@fAr@~Ah@fAXl@p@lALTFNXb@Vd@\\j@Xb@Vb@Xb@p@dAp@fAr@fAbBnCX`@hAjBXb@Xb@j@|@DFp@fAXb@X`@bA`BXb@DHp@dAdBnCvCtEvCtEj@z@DHjAjBRZLRHLDH\\h@NTBDXb@\\h@NTv@lABFlBxCx@pA\\h@^j@LRLTNRPXJPNTBDXb@j@|@`A|ANTHL^j@NVNTr@hAJPLPHN~@vANRLTNVn@`AZh@LPNT\\h@NTNTLT^h@LR^j@\\j@NR\\j@LR|@tAXb@R\\@?DHT^p@dA@@Xb@PVLTJPRVLRJRX`@FLJN^h@LTl@~@\\h@BDJNLR@@LTPTLTNRJP@@NVFHDHRXZd@LRNTLRNTNTLTl@~@@@JNNTNTNXLRNRLTNTLRNTNTLTNRLTNRNRJP@BNTDHf@v@\\l@NTNRLTNRLTNRLTNVNRLRPVLRNTFJb@r@NTNRLTNTLTRX\\f@Xd@PX|@rAZf@\\l@\\h@NRV`@FH\\h@LTLRHJd@r@LR^l@l@`Ax@pALPPVFJd@p@LPZ`@DHPVZ^BDVZVZ@BZ^B@n@t@RTNRPP@@^^PPb@b@PPJJBBPPb@`@`@`@XXJH`@`@LLBBPN`@`@b@b@b@b@PNRRHHVVr@r@RPNNDD\\\\PPNNt@r@t@t@RPbA`At@r@PRdA`AHJXVNNPPPPPNNPPPPL@@NPHHFDPPPPPPNNHHFFPPPNNN@@PP`@`@RPNNNPPNPPPNPPb@b@NNPPPNb@`@`@b@PNRPNPPNBBJLPPPNPNPP|@~@FDt@r@d@d@^^xAvAb@b@FFXXr@r@`@b@`@b@X\\FH^b@`@f@^d@BDZb@V\\FHPXLN\\f@FJFJLP\\j@V`@DHPXJPJRNV\\l@Zl@Xl@NZ@?Vh@Rd@DHXn@Xn@Vp@Xp@Vn@L\\HRd@jAVp@HTXr@Vp@Vp@Xp@Vp@Vp@Vn@Vp@Xr@Vp@Vn@Vp@Vp@DHRf@Vp@Vn@Vp@HPN^Vp@Vp@Vp@Vp@Xp@BFPf@Xp@Vp@JVJVVp@Vp@LXJXVn@Vp@Vp@Vn@Xr@JVJXJVJVVp@Vp@LXJTJXLXJTLXJTZn@LVLTLTLVBDHN\\j@LTNT\\h@PTLRNRRVHLb@f@NRPRNPPPPPPPPPNPPNPPPPPNNPVR\\^RPTTVTh@h@@@lBhBDDd@d@PPPNPPRRDDHHVTLLJHBDRPBDJJPNPPPNPP`@`@b@`@PNd@d@NLPPPPvAtABB\\\\@?ZZFFr@p@b@`@b@`@d@d@^^RPNNRPPPPPj@h@FDvAvANNRPPPNNb@`@PPPNPPPPNNd@b@b@`@NN`@^b@`@r@r@jAfA`@^nFhFVT`@`@PNPPhBfBhAdAVVXV@B@@LJPPlDfDBBXV|@|@d@b@PNNNJJf@f@b@`@PPPPDDJHNN@@NNRRNNNPb@b@JJDDPPDDHHPPPR`@`@`@`@@@Z\\DBPRNNPRPNJJDDPPPNPPNNv@t@PPPNPPPPPNPPPNPPPPPPPNPPb@`@PPPPNNRPPPPNPRTRz@v@ZZ\\\\~@z@JJb@`@HHDFRPPNRRLLRPNPPNRPNNRPPPd@d@p@l@@Bb@`@NNPNRPNNb@^RNVT`@Vd@Xh@VNHVJh@Rh@Nh@NXFPBXDd@FD@N@T@T@J?`@@R?T?TATATAb@C`@ITCTETEREd@MXKRIB?PINGBARIRKTMPKRMRMDCLIb@[LKBATQDC\\W^Wl@a@DELIPORMJIDERMPOPK@AROPMRO@ANKROPMHGHGRMPORMPMFEJGPOROPMRMDELIPMPMRMRKDCLIPI@ARKJEFERIh@UNE?ABAHCFCRGTGRGTGTERGTERELCpAYJATETGTERETEVGTETEVEPETETGb@I`@Kb@Kh@MPGBARGTGRGRGTIRGTIz@Yv@WFCRITGRINEXK\\KFCVKRGNEDARITGRITIJEFARITGRIRGLEFCRGTIRIRGJEHCTI@?PGPG@ATGRGTIRGRITGRITGRINEXIRITIRGTGRITIRGRITIRGRITGd@OXKRITIRGRGh@Qh@QTIRIRGTIh@QRIRGTIRGTIRGRIh@QTGvBu@v@WnFiBTIB?RGJC@ALEz@Q`@Ir@In@E@?@?\\A`@An@?`@Bx@Fl@HD@`AR|@XhA`@d@Tb@Pb@RNHn@V|@^jA^tAZbALz@Dh@@^?h@Aj@EvAOjBc@hFcBlBo@fBm@bEsArC_AdBk@bA]v@WxDoA`@OzBs@n@U`@M~@[`@KVIn@MZG\\GLAf@Gr@EdBG`CI^CtAKLAf@G`AQl@OhA[NE~EyA^KPGZK~DkApAa@rDgAzIiC|Ae@lGsBx@WnAa@FCfBk@VKvC_AjFcB|Ag@HCrAc@x@WlAa@JCTG@A`@KFAZGXGHA\\E@?^EPAPAH?r@CH@h@?\\BN@D?L@j@FXDJBf@JZFXJHBVHRHRHf@Tt@`@JF@@PJLJHFh@b@HFVRpAhABBh@b@^\\hA`AxAnAzApALJNL\\XzApALLHFHHFFRNxBjBbDpC~@v@r@l@FFJH^\\f@`@dFlEfBzAbAz@zAlAd@\\DB\\T~@l@RJbAf@n@X`A\\d@NlAZt@Pj@H`ALfAHv@Bp@@d@?n@A`@Ar@Cj@EZE`@Eb@IH?\\G^Ir@Qb@M`Bi@nOoFvEcB|Am@tBq@dIsCFCDCDABABA@?BATITGZKVGLEZG~AUBA`@GFAz@Kv@M`AO^EZETEdAOb@I~@M|@MNCXEpBYB?HADAB?B?XEHA^El@EZAL?TA^AB@j@?n@?dAFbBP~@J~@N`Eh@bBTz@Jd@HD?B@@?B?@@@?h@Fl@Jv@Jf@DD@tAJv@DJ?H@r@@N?p@?X@l@AJA^AlBIn@Gz@Kb@EHAz@OTEHAREPED?BABABABAB?@?@?@?LEd@MXIj@QHCh@Or@YTIl@Sb@ObA]v@Yl@SbBk@b@QfC{@b@OxEaBTG`@O|By@rCaAZKbFeBJEzBw@ZK~@[d@MfAUr@Gh@El@ERAr@GHAH?lAKv@GTA@AlCSt@Gp@Kv@QNEDAVGp@Sz@YdA_@xCaAFCvDoAfDiA@A\\KvBu@NEjDmANEzAg@LEp@UhBm@fBm@HCrFiBxG{BTGbCy@NEbDgA|Bu@^M\\Mv@SbA]n@Sp@[fA[jA[TGhAYTETGbAO~@MHAXEH?b@Ex@EnAEf@C^?X?dA@f@@z@F|@Hx@Jv@Lj@Jr@LvA^bAXp@V@@HBTHh@RVLB@\\PB?|@f@@@\\P@?@@z@h@zAdABB@@l@d@LJv@p@bA`AnAtAz@~@HHLPdAjAt@z@RTLLj@l@^b@b@d@b@d@hArAZ\\`AfAl@r@FFzBdCPRdCpCtA~A`DjDnCzCDD\\^fAjAh@j@~ClDFFXZdCnCrAzAXXpCzCr@x@bBhBbChC|@bAr@r@LNf@h@pBzBtD`EfAlAZ\\bAhAz@`Ax@z@n@p@hBnBt@z@jDvDbDpDTTTZrCzCTVVT"
                     },
                     "start_location" : {
                        "lat" : 44.2939567,
                        "lng" : -78.28306529999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "37.8 km",
                        "value" : 37767
                     },
                     "duration" : {
                        "text" : "21 mins",
                        "value" : 1247
                     },
                     "end_location" : {
                        "lat" : 43.8394068,
                        "lng" : -79.0697651
                     },
                     "html_instructions" : "Take the exit onto \u003cb\u003eON-401 W\u003c/b\u003e toward \u003cb\u003eToronto\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "{g~jG``{~MHNFLRT`@f@fBxBRXNRt@`AHJPVXd@T`@^z@DLJVZ~@Lb@Nr@H^Lt@DZBXBTBR?FDl@H|A?FJvBBZ@T?BDhABj@H|B@\\@VPzFD~AB~@@H@HNh@?ZD~AJdDJ`DBp@HrCHtCBp@f@xPBjAFxAHxB@T?PBz@Bp@?D@b@?DHxB@Z@p@Bp@Bp@Bn@DvA@p@Bp@F`B?@HrCNjF@JNvF@XBz@DnALdETfH@r@Bp@F~ATjHDzAJrCHpCFhB@JTbI@L?DBj@JdDHxCF~BNtFLnDLrEHjCNdFHpBFtBPtDLdCNnCBXB`@XfERjCPhBNfBp@lHVzB?HHp@Fd@@N@JJt@PxAHl@Jx@NnAz@rFz@|FHl@?BBLTxAb@dC|@vEp@hD?@XpA@F@DXrAH^@D^bB@DZrAhC|J@Hv@rCPh@l@xBFNh@hBbCvHt@zB|BnGjC~GbBhEbFnMRf@Pb@r@jB\\~@f@rAn@bBpAdDFPJTL\\BFb@hAn@`B^bA@?@DXt@JT`@fADH?@`AfCr@pBN`@Tp@Xx@l@pBNl@Pj@FVl@dCFTv@vDP|@b@fCXfBVlBDd@L|@Dj@Jx@D`@HjAZnEV|DDp@Dn@Dp@F|@LfBVxDLtBDh@Dd@R`DHjA?@JbBRvC\\dFLjBFjANrBNdCHnAFj@Bf@JtAD~@Br@j@`JVzD@P`@fGLhBNvBFbA@Jf@zHb@zGd@hHJ~AZ|EFr@?B@JB`@?@@JHrABd@TtDBT?HBZ@N?D@HvAfT`@lGBXNzB@LHfAfA`QBZNxBDp@HdAVrEJtALfCXrEp@`JPhCZ~Eb@vGF|@|@jNZ~Ed@zGb@|GNlBTlDr@nKBf@RzCJdBFz@ThD`@rGNxBF`AXlEPlC\\hFJvAR`DTpD`@fGRzC\\jFh@hIP|BFdAR`D\\`F^zFB\\R`D?BPlCFt@Dv@FtAFxADzABjA@dA@hA?p@Ap@@vBAbAM`EKnBQnC]lDQvAQnAa@rCs@tDe@rB_@xAY`Ac@|A[dAc@rAm@bBUf@c@bAKX_@x@Yj@INc@|@e@|@OT[j@e@v@eEzG_FfI_AxAy@|AU`@}@dBGPUd@]p@qBpEmAzCcB|E_BhFeBvGc@fBg@|Bk@rCk@~CSrAO`A]hCSzAUlB]vD[lDGl@Gt@Ex@QtCWrGCbAE`BC`BCfD?dDDzHBfABfBDhADtAPxDN~CDl@P~BTjCLlAV`CPzAPnA^tCL|@N|@h@vDHn@Hn@fAtHJv@fB`Mn@nEHl@BTDTDVHl@r@|EjAlIp@|EHh@`A~Gd@bDvAzJdAnHL~@DT^nCp@tED^`@tC^lCNbALt@@JVjBfArH~A~KVlBHh@?BHd@VpBLx@L~@`@lCxBxON`AD\\Hb@T|ANbAV~AxAlHp@dDv@rDlAzFj@jCLl@Np@FZDPh@dC|@lEnAhGx@xDv@dEThAl@~CTpAb@`CHh@TpAb@tCNx@PdA^fC^lCHn@F^BN^lCJn@Hn@`@lCdApHz@fGRxAt@dF@FBP@B@J`A|Gt@lFJl@j@|DHn@r@`FrAfJ@Dh@vD^nCv@lFjAjIbCzPr@bF`@rC@Dj@|Dn@vET|AHh@?D@FHd@NhADTHn@Jl@T~AL|@XhBFd@`@jC@NF^L|@NdARtAXpBNnARbBH|@LxAFx@HjAB^Fx@FxAF`A?TFvAFzC@n@?D?R@lA?r@@\\AdA?FAtACnCGjCGjDGpC_@dPS|JKtFAHQlKGtCc@tSOnFALCpBAd@E`BAp@An@ItCCv@Aj@?DAj@GlBAd@I`DKxDChAElBKnF]`QErACp@A\\EtBCdBEvBA~C@`A?z@?ZBtBFbCF`BDjANlCVxDr@tIb@pF?@ZbEZ`Ef@bGHhAJpAFl@r@|I\\nEb@vFt@|HZbDV|B\\xCf@dERvAVrB|@fG~@~Fv@tEBNz@rE~AfIJf@n@`DxBzKrApHJn@Jl@@?TvAf@~Cv@|Er@pEdAzGJl@l@|DhAlHZnBRjA^`C\\~BDRx@pFJn@V|Ax@pFDZHh@BRPhARvADZL`ARvAXxBLjA|AjMb@xDDZDl@d@zDnA`Ld@rDd@rDdBvLp@nEv@tFBLn@|Dj@pDf@|C^~Bd@xCJh@PfAl@pDRnAN`AfA`Hh@bDh@lDfAlHNlA@@D\\BPLp@XlBrBbPl@xER~ARbBBTTrBd@`EVvB\\zCTnBr@pGRvANvADLBNr@hG?@tCtVr@hGPzAhA`KFp@t@|GHn@Hl@NlAFr@L~@@@l@tE^pBZrAd@fBNh@`B~EdAxCb@lAFNzE|MRh@BHr@nB\\|@HZzCnInFfOZ|@d@nA\\|@l@`Bh@tA^dAt@nBXv@HT`@lA@DTj@Pj@"
                     },
                     "start_location" : {
                        "lat" : 43.9054239,
                        "lng" : -78.622894
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "38.0 km",
                        "value" : 37966
                     },
                     "duration" : {
                        "text" : "22 mins",
                        "value" : 1314
                     },
                     "end_location" : {
                        "lat" : 43.7198638,
                        "lng" : -79.49368
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork to continue on \u003cb\u003eOntario 401 Express\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "ikqjG`iraNd@~@Zx@HV^bAZ`Ad@lA`@nAj@`BL^Tn@\\~@Zz@FNt@pBzAfEn@fBPh@fCfHhCfHpD`KzAdEd@rARh@fFtN@Bl@`BhChHPd@nAjDb@lAPh@HTTl@xCnIRh@fCdHRh@HRhBdFRh@tI~UZz@hA`D~@jCJ\\JXN^L\\`@fAtErMhDpJp@fBz@tBd@bAdC~EfAlBxBlDnBxCl@~@n@bAfE~GVb@bBlCdAbBdBzCVb@pC|En@hAFJnBlDn@hAfAlBLTxClF`@r@vF|JbG`LxBfEjCbFlHlNvBzDd@|@\\p@@FXl@pA`CXj@Td@Th@Zp@b@dA`CnFRf@Tf@j@lA^t@d@|@Td@@BN\\BDVd@Td@R^BDl@jAPZDHdArBLXFJl@jAt@tAPNPZt@pAr@nAp@jAj@~@j@bArAvB~@xApBbDpCjET^BFbDlFf@v@p@bABBVb@f@|@h@`APV?@d@x@NZDHp@vAXn@HTN\\?@Rd@?@BFd@rABDZfATx@?@HXBJPt@Nr@H`@V|ANbALbAHv@Fr@Dl@HrA@RBZBp@BjA?DBh@?f@?F@XAv@AdA?\\GvBGbAOvBO|ACPIp@M`AId@If@SdAYpAm@bCKb@_ArD_AxDSt@S|@W`AI\\ADCHIZIZg@nB_@|Ae@jBg@nBOj@w@|CQr@GV?@EROh@AFK`@I^SbAMl@ADG`@CJG\\EXId@Gf@Kr@Kx@Gl@In@El@Gj@CZ?FC^AFEt@GtACh@A^Cv@Al@Ad@C|@?n@?X?fABrBFzBL|CHfAFz@ZfENrB^xE\\pEV|CJbBXhDJvADh@F`ALrAJxADb@Fr@F|@H~@JpAB`@l@`I|@jLl@pHHpALxA?@LvAFn@Ft@H|@Z~Dv@hKN`BDn@j@fHJ~AFn@@FZbEDf@L`B`@rFTpCRdCZ`EL`Bv@dKDn@ZzDj@hHdAbN?BFn@Dl@Fp@L`BF`AJlA?@Fn@RpCLzA@DL`BTtCLnAJt@Fh@BTHl@Jx@Jl@Lz@TtAZbBRbAP|@FTFVZxA^xAh@lBX~@X`Ap@pBTl@b@lAp@`BfAfCz@hB~@hBh@fAd@~@NZr@vANZXj@r@~Af@dAf@pAd@hA@D^~@DLTl@Ph@Tj@Z~@\\fAHZx@lCRr@^tAj@|B|@vD~@dETbAZvAjAtFXdB\\|AZ|Ah@pC@J\\dBn@pDbAbGLv@P`AN|@Jl@?@Fd@VzA`@nCRrATvAn@xERrAPrADTR~Ah@lE@HLhAJv@Hz@p@~FHv@LhAbAvIv@`HHn@?Fj@~E@FFn@hB`Pj@jFl@dFJdAx@dHd@lEBRx@jHBX^|CFj@NhA`@nDTnBBRn@pF@HXdCP~Ah@rEXzBJp@ZjCHr@`@zCThBt@xF`@rCVjBLz@Fb@FZBPtAzJBRn@jEL|@N~@RxAp@tEBJNdARtARtANdAn@jENhABRBLNbAJp@RpA?FbAxGl@~Dz@bGd@dDx@rF^fCBRZrBp@vET~AT`BpFl_@d@xC~@fGLbAN|@Hj@Hr@D`@\\fCPjANx@L`AFb@DT@H@F@HPfAb@~CR|Al@~DDRj@|Dj@~D`@dDXfCRjCFv@Fv@JnBLlDH`E@l@@x@@dB?zF?fC@xHD`O?@?B?@?B?@?B?@@B?B?D?F?H?F?B?H?H?@Ax@Zb^J~MDt@B`BHtDHfDDzA@d@FzBFlBBbAFpCBp@@p@Bp@F|@Bh@BxAFvC@TLbFHhDFhBFhC@j@R~HLfEDnB@R@n@F`CJtDJfE@n@@^NnHJhGPdJHdF@p@BjBBnADfB?NDrC@t@@XBdA@jA@\\FbDFnDBjB@VBvALrHHpFBbBDbBB`B@p@@p@@p@@LBrA@bABfABpAB~AB`BFzCBjA@rABrA@\\?RBtAD|A@XDvABdA@LDlADlAFjADx@HlBJ|A?@F~@FbAF|@@FDf@@LHrAPnBNzALxADZFf@ZxC^~Ch@tEFd@Hj@Hr@BPXvBFh@R~ABLZ~B@PF\\Hn@Hn@Hn@?BRzAHn@RzA^pCLhALjANbAPxABRLx@PpAJx@PxAHl@@BJv@J~@Jn@BPFd@L~@Jv@Jr@Jr@TpALt@Nr@VpAXnAXpAPp@HZRx@^nA^nAf@|AVv@`@hAb@hAb@dA`@`ABFXn@n@vAz@`Bt@tAb@x@BFh@bAPZpBtDxAlCv@xA\\l@t@vAx@xAZj@j@dAlBjD@?@@BDd@z@dB~CZl@T`@PZ^r@JNLTP\\LVHLLTLTHNDFP\\FLNTd@|@FJj@bApA`CXh@LTHNBDl@fA`@r@Vd@HNb@t@f@~@t@pAj@dA\\l@Xd@P\\NVTb@\\j@l@hAPXJP`@p@Zf@NTPVJJFHHBFDNPBDd@f@DDJLNNPPb@^b@\\^ZFDNLv@l@b@\\NLf@^d@^b@\\FFHFPLRPRP`@^XX\\^d@j@Z`@d@l@b@n@Zh@Xf@Zh@l@fAZj@j@`AHNl@fAh@`AZj@x@xAf@~@j@`AnA|BNV\\n@Zj@Xf@Zj@PZLTLTj@`AZj@Zl@`@r@R^NXXf@Zl@~@dBn@nAJR\\p@HPLTJRP\\Vh@LXd@~@v@`BrBdEP\\l@nAFLd@~@Vf@HLhA~BN\\JPRb@`@v@t@zALVLTZl@d@|@Tf@z@`BhBxD~AfDR`@n@rAHPXj@NXzBpExAtCh@fAb@`ALTBHTh@HPRb@Pf@JXNf@Tr@JZDJPn@Nb@Lb@H`@H\\HZFTF\\Lp@H\\Lr@Nx@Lv@?@PlALv@Jx@DXDZDZDZD\\DZDZD\\DZF\\D\\Fd@BPNfAZbCHl@BXR~AVrBXvBNfADXBRPpABLR~AHn@Hl@Jn@Hn@Hn@DVVvBF`@TjB@@Hl@Hn@?DZ|BL`AFf@R~AHn@BNL`ADXNdABTPnAJ|@Fd@@DVjBL`At@zFJ|@\\hCb@lDL`A^rCn@~EPvAPlAD^PlAXvBd@vDfAlI\\nC\\nCFb@^bCHn@DP\\zBPfANfAh@lDN|@F^`@lCHh@@BBLFf@v@dF@D`AfGXhBf@`Dn@~Dj@nDrArIt@bFPfARpAZrBBNFd@ZvBHd@ZtB|AbKt@xERtAT`BNbAfAtID`@BXFn@Hn@"
                     },
                     "start_location" : {
                        "lat" : 43.8394068,
                        "lng" : -79.0697651
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 953
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 36
                     },
                     "end_location" : {
                        "lat" : 43.7183023,
                        "lng" : -79.5052046
                     },
                     "html_instructions" : "Take the exit toward \u003cb\u003eON-400\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBarrie\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBlack Creek Drive\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWeston Road\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "c`ziGnbedNELAF?BAF?F@F?HBTFr@JjA@TDh@Dj@@JJ`B@RDr@@NBj@?BBh@Bl@?n@?f@?R?p@@^A`A?fA?V?B@f@@H?PBd@BTBTBVHd@F\\DRFXH`@Jh@R|@P|@VrABLVxAJl@Jx@?DD^Hx@F|@Dj@@DLvBJtAF`AADE\\"
                     },
                     "start_location" : {
                        "lat" : 43.7198638,
                        "lng" : -79.49368
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 604
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 24
                     },
                     "end_location" : {
                        "lat" : 43.7174208,
                        "lng" : -79.51262009999999
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eON-401 W\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eMay be closed at certain times or days\u003c/div\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "kvyiGnjgdNFn@d@zIJ`BDz@Fx@?BNxBBh@@PLbBNpC@BZpFF~AFv@?NDX"
                     },
                     "start_location" : {
                        "lat" : 43.7183023,
                        "lng" : -79.5052046
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "72.2 km",
                        "value" : 72241
                     },
                     "duration" : {
                        "text" : "39 mins",
                        "value" : 2362
                     },
                     "end_location" : {
                        "lat" : 44.3472826,
                        "lng" : -79.687607
                     },
                     "html_instructions" : "Take exit \u003cb\u003e359\u003c/b\u003e to merge onto \u003cb\u003eON-400 N\u003c/b\u003e toward \u003cb\u003eBarrie\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eParts of this road may be closed at certain times or days\u003c/div\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "{pyiGzxhdNGP?DABAD?B@f@DfADzA@l@@v@@d@?B?l@CbAAn@CVC^S`BKf@Qz@IZ]rASt@Mj@Qn@_@tAOl@Mb@K^a@pAMZWl@Q\\GLINMPMRY`@MLY\\g@d@QRUPk@h@[TEDCDEJIVq@d@SLg@Ze@Xw@d@ULIDGDg@TMFQHUJUHSHA@c@Lk@PUFUFe@J]HC@}@LQBUDwLfBSBk@HgFt@sCb@gAPc@Fq@J_ALuCb@_ANoAPeAP{BZwCb@wAToAPG@kBX_BTA?G@}HjAwARqDh@C@]DkBXeANeHdAwDj@qInAeAN_@FqC`@a@FgAPcIhAYFmC`@c@F}HjAkBXcOxBqC`@qAR_Df@kC`@c@Fe@HqDh@_LbBqAPi@HaGz@kMlBqEp@sARi@Hq@Ji@H{@Lk@H{B\\iC^_@Fs@H_Fz@]Fy@Lq@JaAN}GbAyAT}Er@YDWDg@F{B\\{@L}@L{HhAsEr@qC`@YD[D_@FuATwBZG@y@JqAPaANsAP_AJsDd@w@Ha@DeG|@yAT}BZkBXiBV}Ch@oCb@{ATeBXeAPcDh@e@Hu@LiAPwATQBu@L{ATqARqARaEl@gHbAyC`@yAPO?aFt@u@LmDf@k@HUDm@HmDh@_LfBqAR{F~@kIrAuInA_@Fa@FQBs@LmBVkC^wDh@mAPeANyDj@eDf@kEp@eCZw@HgBVoATyAR{@JyBVuDXwAJC?uG\\YBiBHA?c@ByCLaBHq@DU@gADc@@eAFy@BM@U@_ERyBJgDNa@@A?qAF}@D_AD[BU@Y@k@Bk@Bk@BU@U@U@M@G?U@S@W@E@E?K?G@M?{@FE?O@E?i@BO?UBE?Q@]@O@G?M@G?M@E?M@I?U@K@W@U@gCLaADU@Q@U@C?Q@E?O@E?O@K@K?S@S@S@K@K?W@U@U@UBU@I?K@W@U@U@U@U@U@U@S@C?S@k@DU@U@I?K@U@U@U@U@U@U@W@U@U@U@U@U@U@U@UBU@i@BU@U@G?M@W@Q@Y@S@U@U@U@m@BS@U@U@U@WBm@B}BNoCPwCN}@Bc@@qABY@U?o@BS@UBS@m@DQ@E?S@i@DWBUBU@SBUBUBU@SBWBSBM@]DSBUBUD]FM@q@HMBwAVgDf@o@HqARsDl@oAN_@DuBZSDmFt@kEp@sB^k@H{Er@_D`@_D`@u@LG@WDA?I@WDa@FC?k@JUBMBqDh@iBXeKzAC@E?sBZyAVyDj@G@E@UBy@L_BTWDG@_@FcDd@eEl@M@c@HiAPe@HSDYDWDC?iAPiAPaC\\oBXc@HiBVc@FkMlBgAPa@Fq@J[FYDC?wC`@{@LQHgANy@LE@_IlA}Cb@SBa@Fc@Fc@Fi@HA@[Be@HmC\\m@J_BTc@Ha@Fc@FUDM@oDj@_@FqC`@mAP[DmC`@[D{Cd@iDf@UDC?_@FWDqATG@QBYDm@JQBYDa@FUDk@FE@O@SBeAR[DE@s@H_@DsJxAA?qARaC\\{ATc@Ho@Jc@Fy@LmBXqFv@_ANq@JmFv@}Dj@k@H}Cb@m@J[DiC^yB\\mP`CwCd@QBYD[Ds@JC@QDaANI@gAPeANi@H]Fa@FqARWDmAP]DeAPK@eC^aANcEn@{B\\eAPwCb@YDcBX{B\\aC\\gANa@FYDqAPgBVy@Js@JoARmC^u@Ls@JgANeALqAJOB{ANa@Dc@D_@DWDiBXa@FwEp@e@HsBZqAR]D[Fg@FoBZeNrBa@Fq@JcDd@a@D[FUBKBK@A@G@]Dm@JiBVa@F}RxCqAPq@JwB\\yB^w@LSD{@Lw@Ny@P_APm@LOBmAR_ANq@JyIpAeLbBiEn@{Cd@oAR}@LsBZa@F_@FmBXc@FsEr@sDh@k@H_@Dg@JiC^sBZ[Dc@Fc@Ha@Fi@HI@YDSBOBa@Fc@Fc@FG@e@HWDc@FMBiAPgANs@L[D_@FqARQBcANw@Jc@Fe@Hw@JuB\\i@H[DiC`@wARWD{B\\eANqCb@gANs@Js@J]FcANaAN}Dj@qCb@_C\\cBV[FkAPaBVSB_BTuAT_@DoARiBVYFc@Fk@H}@Lc@HiBVa@Huf@jHsEr@uCb@G@eC\\uATw@JeDf@{B\\oDh@kDh@c@Fi@HiDf@YDiBXcANo@HmBX_CZyFv@oAPa@Fo@HaC\\qDf@kMfBwFv@mAPiGx@sEp@eGx@aFt@cC^aANMB}@Pu@LqAV}Bh@iDn@wLzC_ATo@NuA^eCp@G@iCj@sBb@kCl@u@PoBb@QDiCl@MDUDeB^QDQDa@Ja@HgBb@u@Pa@Hc@Ja@JIBYFa@J]Hi@Lk@LYHeAVa@JeAVgAVeAV]HiAXgAVa@J{A\\k@NiAXsAZuBh@{A\\}Bd@gARkB\\{@LqATi@HkATA?aBXA?g@Jy@NE@kAPQDm@JSDcAPI@w@LaAPw@LKBaAPC?}@NSDMBa@FYFE?YFG@_@FA?_@H]F[DmAVyPvCe@F_@Hg@F}@PSDiCd@K@gBX[FiBZaANaBZ}AZ{Bb@A@WDeDh@oEr@_APE@cBZo@Ja@Hi@HuAZw@LkAVg@JC@c@F]F{ATA?{Bp@m@RKBUJA?aBp@cAb@IBu@\\{@^_Bx@e@RyAz@iBjAsBzAmCvBwBjB}AnAc@\\}@t@}RfPwBfBw@n@IFwE|DQJcAz@SPeEtDs@n@sChCeA`A]VONGDwCdCiEjDWRA?uAjAcBvAq@n@gA|@q@f@ONQN_Av@WR{AnA_@Zw@n@a@Z_@X}AtAw@l@GDeJvHyBfBuJ~HyCfC}E`EwAhAcH|F]XA?wC`C]XA@e@\\uCnBuC~AqB~@cAb@kBx@qBl@_Cj@_APMBa@FaPjCgAPoBXE@]DgC^gAPaAPgANiBVo@H{Dj@mCf@qS|CwGfAi@Jc@HoDj@MBUDa@F_BZYFE@e@FiBZc@FeAPmCb@k@H[DuB\\aC^oDj@kCb@e@Fa@HwF|@qBZSBUBy@LiMnBc@Hc@Fa@FMBeAP{Dl@q@JoDj@c@Hq@JSDM@y@NsEr@kAP{Er@QB}Dn@oATwATuF~@}AVwBZG@WDI@KBK@WDqCb@a@F]FI@iEp@mAP_Df@kBXIBs@Ji@JI@YDyB\\[DgDh@}GdAyAT_G~@[Da@Fy@NsBZK@WDk@JiBXuJzAI@WDIBoHhAKBsARWDSBIBiBX}ATa@HK@m@J_@Fc@Fc@Ha@Fc@FeAPgAPeANwF|@i@HcBVmCb@mC`@oDj@uEt@cK~AwF|@kC`@uEt@mFx@qDj@oDj@aJvAc@FoEr@C?c@HsEr@G@mAN_AL_CTqDXk@DY@uBJA?kCJe@@cDJq@@c@BoCHc@@oCHc@BgXv@uIXqIVeBHsBFmBDyELeFNqDJsCJqBDaENwBHuAD}ADaELy@B}CJcELg@@c@BwELuM`@m@BA?i@@oCFc@@c@@}@BI?c@@c@@c@@c@@_@?C?eENiCNy@Fc@D[BG?o@F}APQB{BXE@eBVg@H_Dj@qBb@_Cj@o@RE?]JwA`@sA`@eBh@yBx@sAh@a@NA@_Bn@gEpBC@gElBsLlF_A`@A@_@PE@yDdBmF~BUJUJi@Vk@VUJ_EbBUJ_FtBa@RkNhGw@^qClAeF~Bc@TA?uDdBmAd@k@V[LcEhBe@Ru@Z{FfCcDvASHIBcA`@e@Po@VkC|@sBn@aBf@}Ab@y@RYFw@RaB\\kB\\uCh@sB\\s@JkDn@YFc@HeAPC@M@QDC?c@HeBX[FsCf@C?eARc@FIBkCf@gDj@UD{Ex@mCd@q@JYF]Fa@H_Dh@gEn@{B\\wAX]Hg@HYDcG|@gB\\C@iEv@QD{FbAgB\\aEt@kBZuHrAs@Nq@JwCf@m@JeAPk@J{@NeBZUFuB^cDl@KB{@NaAPwCf@cEt@aDh@mF|@kJ|AyB`@aEt@mDl@eAPqDp@cBXg@HqAVmDj@cFz@wDp@s@LoBZMBy@NgCd@_C`@yB^uAVeAPsDn@kCd@iB\\kCd@kBZoBZ_Ej@iAV_B\\}B^aBXcBX_BXcBXaC`@oB^qDn@aDh@mCd@OB_@F}AXkF|@gHnAwDp@]FaC`@oB\\sCf@KBaC^qB^oB^sDn@}Ch@}Bb@kCb@aBXgCd@m@JgItAeAPkEt@}AXaAPI@UDaHlAk@Jo@J]Fc@Ha@FcF|@[FG@c@FUDIBe@H]FE@[DoCf@_BVcBZoB\\c@FiARy@Nu@Na@F]FkATc@Fg@J_ANc@H[FyB^kATUD]FG@[FsAVYD]Fe@F_BXkARG@a@H{AVcBZeDh@aBXsCf@gBZc@HYDk@Ju@LO@cALkAJM@UBs@DgADcAB_A@w@?m@?KAW?K?C?u@Ce@AI?SAqBGu@A_ACy@Cs@C_AC}BGs@AEA[?A?]AkAEc@Ae@AcACm@Ac@A_@AC?oBEUAaBEa@AoCGoCGkBGE?aBEg@AqACYAoCGQAiEGqDI_@AoCGUAMAo@C{@Ac@AU?MAgACiBEe@Cc@AkCGC?gIQiCE]AE?kDKo@Ay@Cm@A[AoACYAqACQAw@?eB@mBFW@i@B[@_CVmDf@cANUDwF|@cFv@a@FMBy@LgAPC?cAN{@Li@HkBXiBXmC`@{@N{@LiDj@I@qCb@_Ft@KBoJtAmAPoAR{AT{@LuATqB\\SDcGbAe@HSDuKfBgAP_AN"
                     },
                     "start_location" : {
                        "lat" : 43.7174208,
                        "lng" : -79.51262009999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 467
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 58
                     },
                     "end_location" : {
                        "lat" : 44.3514629,
                        "lng" : -79.687809
                     },
                     "html_instructions" : "Take the exit",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "oqtmGp~jeN[GMCMBs@Fw@FG?q@BM?W@K@kBFS@O?Q?]?WCuAI}@?e@?m@BK@M@]Du@JE@"
                     },
                     "start_location" : {
                        "lat" : 44.3472826,
                        "lng" : -79.687607
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "64 m",
                        "value" : 64
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 143
                     },
                     "end_location" : {
                        "lat" : 44.3519563,
                        "lng" : -79.6877009
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "skumGx_keNSc@?CA?A?SBq@LE?"
                     },
                     "start_location" : {
                        "lat" : 44.3514629,
                        "lng" : -79.687809
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "254 km",
                  "value" : 254217
               },
               "duration" : {
                  "text" : "2 hours 32 mins",
                  "value" : 9145
               },
               "end_address" : "20112 ON-69, French River, ON P0M 1A0, Canada",
               "end_location" : {
                  "lat" : 46.0282,
                  "lng" : -80.59294109999999
               },
               "start_address" : "201 Fairview Rd, Barrie, ON L4N 9B1, Canada",
               "start_location" : {
                  "lat" : 44.3519563,
                  "lng" : -79.6877009
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 669
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 215
                     },
                     "end_location" : {
                        "lat" : 44.3568101,
                        "lng" : -79.6914123
                     },
                     "html_instructions" : "Head \u003cb\u003enorth\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wnumGb_keNa@FKIOEC?K?I?G@a@BE@M?M?AAKAG?I?I?A?G@EBA@A@?BAB?DAD?p@?X@hAe@d@]d@mA`AkBdAIDEBOHqAn@o@\\_Bz@wA~@_Ap@STy@z@"
                     },
                     "start_location" : {
                        "lat" : 44.3519563,
                        "lng" : -79.6877009
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "10.2 km",
                        "value" : 10187
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 344
                     },
                     "end_location" : {
                        "lat" : 44.4237691,
                        "lng" : -79.6531476
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eON-400 N\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "amvmGhvkeNw@n@m@h@oDhD[\\[^yDrEkA|AKLWZCDu@`AUXmDjEa@d@mAxAy@`ACDIH?@k@p@]b@uBfCcGpHaBnBu@~@e@h@GFuBdCUVwA~AYZqBxBmDxDYZMLSTIJOPMLQRMLKJSVUXGHi@n@e@j@Y\\[^wDtE[`@IJEFYZkB`Cy@bAYZeCtCwA|Ao@j@y@t@mBxAGDo@^iAj@s@Xu@XG@UHSFA?A?EBwAXg@FyALkADgA?oAII?wAQGAcASu@OKEgA[cA]WMICa@QCASK]MaCeAkAe@qAi@[OyAo@eAc@KEaDuAmJ}D{@_@SImCgAwEoBmF}BaAc@QKu@]m@]o@_@o@a@w@g@u@g@kA{@s@g@w@k@q@i@wCsBqFaE]Yc@[_@Y}@q@}AiAAAsCuBiAy@s@i@uLyIq@g@cBoAwB_BqB}As@k@o@k@[WQQSQ_@_@EE_A_Aa@e@GIeAmASYMO]a@MSMOAAo@{@gBiCi@y@y@oA{CsE?CkEwG_FoHmIkMs@kAcBmC[i@[m@g@aAYo@Wk@_@{@Qg@Oa@i@yAWw@YeAACK_@ACKe@m@iCo@{Cq@}D{AaJ?AkCgOSiAgAoG[iBG]E]ESESe@mCKm@y@wEo@qDEWcAgGgCqN}@oFc@iCSeAWyAg@_D[cBSkAQaAMq@O}@Qy@U}@Ok@GUQk@Qk@Sm@Uo@i@oA_@}@a@w@a@y@S_@IKg@y@c@o@QUSYe@k@wA_B[W?CoJeGkFcDcCoA"
                     },
                     "start_location" : {
                        "lat" : 44.3568101,
                        "lng" : -79.6914123
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "138 km",
                        "value" : 137659
                     },
                     "duration" : {
                        "text" : "1 hour 13 mins",
                        "value" : 4409
                     },
                     "end_location" : {
                        "lat" : 45.4366808,
                        "lng" : -80.1228842
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork to continue on \u003cb\u003eON-400\u003c/b\u003e, follow signs for \u003cb\u003eOntario 69\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eParry Sound\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSudbury\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "qocnGdgdeNG[SUs@g@[SOGi@[OIu@a@e@]IG[We@e@]_@CEY[k@{@c@q@IKQUMQc@a@UOWS]O[MA?YIUGUCm@Ea@?e@B[DSDg@LIBYLc@V_@VUV]`@[d@QVCDS\\Yl@]r@w@pBO^CDSh@Wr@kAzCADaA`C_@`AADADSb@MXi@hAc@t@S^ABQZa@l@EHg@p@[d@CBA@UX[\\_@b@]\\A?]\\WTaAx@]XaFfE}@t@CBWR_@ZSPIHIFw@n@SPEBKHSP]XGH[VWR]Z]ZyAnAm@f@aAx@kJ~H}E`EWTGFUP{@t@_@X]X]Zm@f@]XQPKH}@r@]X]XGFu@l@}@r@u@n@_DhC}@r@_@Z[V{AlA_@Z{AlA]XkA`AmA`A}@r@{AlAKJQNyC`C{AnA]XQNeCtBOJ}@r@yBfBA?ML_BpAk@b@GFiA~@i_@rZiGbFmGdFmEpDeBvAeAx@kB|AcAv@w@p@qAhAUP{CnCuDdDMLOLqCbCMNiA`A}@x@wBlByPlOsE`EyFfFwCfCaBzA]XyArA]ZqE`EA@i@d@i@d@o@j@}@v@y@t@s@n@aBxAsF`FoBdBs@l@cA~@{@t@wBpBq@j@qF~EyClCEDsAlAEB?@aElDyDjDiBfBeD|CEDkAfAMJs@t@c@`@wJdJyGjGi@f@o@n@m@j@CDg@b@SRIFm@j@CBaBzASR]\\IFq@p@QPSPo@l@A@]\\IFuBpBeFxEuApAABIFSR{@v@IFONCBMLmDdDSR]ZGFON_A|@]Z]ZWTa@b@SRIH]Z{@v@]ZCDWV_@\\uBlBYVCBmAhAGDCB]Z[Z{@x@YV}AxAuBnBsCnCiHzGaJrIeGxFkHzGeG|FgF|EqDfDoH`HoCjCaA`AcCzBo@n@gE|DoEbE_@\\_@^aDzCoEfEoCfCi@f@yBtBcB|Ac@`@gI|Hi@f@oDbDqBhB]ZCB{AtA}@t@o@`@m@^m@^MD_@RgAb@g@P_@Jy@TeKdCyTrF}Cv@kFpAi@LeAVa@JkBd@WDk@N_ATgGzAQFoBd@mAXmCp@gATeANaAJk@DM?]@sABaAAgAG{@Iu@Kq@Mk@My@S{@Y_A_@}@a@WMu@a@y@k@q@e@m@g@uAoAu@q@WUk@i@{@s@QQyJ{Is@m@c@c@g@c@oAiAeAaAuAmAACw@q@s@o@gB}AqLsK[[}@w@KGwCoCo@o@{CmCwCiCiB_BuBsB_@a@_@a@aAeAi@q@a@g@e@m@y@gAu@gAo@cAcBqCsAeC{@gBWo@c@aA{@yBu@sBy@cCKWQm@Qm@[iAc@aBm@cC_@_B_@yAu@}Cm@iCe@mBm@gCo@iCm@kCo@iCw@cDo@iCm@iCo@iCm@iCo@iCo@iCY_A[eAUs@Us@c@kA_@}@_@}@i@gA[o@[m@{@yAe@w@gE}GqCqEoAqBAAOWGIOYoAoBCEq@iAe@u@KQc@s@qBcDGKQWGIuBiD}BsD?AYa@cBqCy@sAWa@_A}AkAmBGI{AiCaB{CQ_@m@sAuA{Cw@aBu@eBaAwBmAkCeA{BoAqCo@yACEQ_@q@yAO]q@yAg@eAM[s@{AO]u@aBQ_@c@_As@_Bu@_Bu@aBu@aBc@aAQ]u@aBg@gAKWu@_Bm@kAKQKS_@q@y@wA}@wA_AuAaByBw@aAgJaLaEaF}EaGwJuL}AkBmA{AaAgAgAmAaCaCsAkAIG]Y_@YWSMIu@i@m@c@sBqA}AaA}B{AeMaIsCgBgBiAc@Y[UCA_BcAkKyGu@e@uEwCiBkAUO{CkBoAy@sCgBkAw@yBuAe@UiCcBc@YuA{@IEu@e@[Ua@WaBcA?ASK{@k@kAu@a@W[OGEGEk@[{@a@i@WoAq@m@WQGg@QSIk@Qm@SOGUISIUIMGiDiAqC{@QIaBg@QEiFeBuBq@o@UmAa@cGsB_Cw@gCw@s@Ua@Ma@OsDkAqAc@y@Y[KmBo@e@M}@YuG{B_EsAcA]aDeAGCME]MwAc@oBs@wCaAgBi@oBq@{@YaCw@EAsDqAkBm@w@WaA[sFiBeBk@gBm@yBs@}@[yBu@mGuBuHiC_D_AOGUIMESIMEQGsAc@UIeBk@qC_A_FaBgCy@A?SIUG}Ag@AA{Bu@ICCAUIwDoACAOGICmRoGy@WaA]gFeBeA]a@Ma@Oo@Uu@WkDiAA?gC{@gBk@UIKEa@Mw@YICA?GCMEKEeA]a@McA]qAc@w@Uc@MGAw@Sg@Kc@IaAQkAQA?{AMqBKQ?i@Ae@AgB@o@D_@@yAHgAJc@Fy@JKB{AXaAPcCd@}@Pe@Ja@JI?ODoDp@c@H]HYFu@L_@HiB\\kB\\_Dn@sE|@eARyGpAeATA?yGpAe@HkEz@_Cb@iBZeBVu@HC@_@DC@aBPyBR}@F]BE@oBJaAFoCNsDRC?_@BsDPuDR_@Bc@BgCL{G`@qCLs@BeCNc@BaBHM@}Jh@k@Bc@Bc@B{BLgBNeAPw@NODi@NmAb@C@y@^i@Xa@R[Rc@XA@_@Vk@d@}@x@w@x@y@fAw@dAg@x@OVS`@Q\\wA|CuC|Gi@nAUh@]z@Uf@k@pAo@|ACF}@pBo@|AWf@MZUf@_AtBA@IP_BxDg@lAS\\e@|@Wf@e@z@e@|@m@bAGNa@l@e@r@q@~@a@h@o@t@e@h@o@p@c@b@a@^{@v@]XA@c@\\m@d@g@^c@ZYREBy@j@s@d@e@\\e@X_@TGDaC~AuA|@oAz@}AdAoAx@{BvAMJoBrAEB}CrB_An@yCnBc@X}CrB}CrBA?UNGDA@SNsD~Bu@h@MHQLKFsJnGyA`AyJtGwMxIaN~ImAx@_@VsD`CiCdB_@VA@eG~DeFdDoFpDmAx@cAn@s@d@c@Z}@n@c@ZgAz@u@p@CBKJON]\\WXa@d@s@`AY\\A@Y`@AB}@vAKPWb@Wd@?@Ud@EHu@~A[v@Sh@A@K\\a@jAUr@ELYbA{@xCa@zAo@zBADQj@y@xCCHi@jB?@Oj@GRIVQl@]lAIV}@bDGXwAbFUx@Y`AOf@q@xBc@nA_@|@_@x@m@rAMRy@zAu@jAY^_@h@]d@MRa@d@q@t@gAbAu@n@w@j@k@`@q@b@SLaAd@o@\\m@T}Ah@oBf@uB^y@Ja@B]Bg@BYBK?[@Y?s@As@CsAI}@K]EoASo@M_@Ko@UWGUIQGSGUKi@Wk@[OGQK_@UkAq@eAq@CACACCCACAAAA?AAA??AA?GEeAm@QKoBkAo@]gAm@gAq@gAo@_GkDUOs@c@kC{AGEAAsKmGqAw@aAk@kC}AkHgEmAs@uAq@e@Q{@e@cHkECAa@SeDqBi@[UMc@WwAy@_Ai@_@QECQIUI_A_@k@QWIYIe@Ka@IKCkASkAKwAG}AAwABmAJ}AP_Cf@m@NcA\\u@^aBx@o@\\[Tc@ZA?kA~@y@r@y@n@w@p@gA|@UPa@Zg@b@s@h@?@]VKHoB~AA@SPGDA@]V]Z_Av@_@XYTEBIHOLaAx@_@XWTEDA?URKHSNUPu@n@OLGFUPgBvASPoDxCED_@XMJONMJOL_@Xm@f@MJQLmCzBw@n@qC|BaCnByCdCeFdEkA`A]V?@]X}D`DYT}@t@]XaAv@_@ZkBzAcCrB]XKJOLGFURw@n@i@f@cAz@YVCB_BdBk@v@m@z@kAnBA@cApBKTc@bAw@xBSn@Sp@M`@GNSx@Mj@S|@O|@ETG\\OfAQrAQdBa@`EOxAWpCSjBe@lEA@WvBIp@?@CRYzBYtBSvAMx@CPE\\Ih@ADSzACRSvASxAi@bEw@nFUfBw@bFWxAYnAMp@S`Aq@~Ci@xB_@fBCHIVSv@]rASp@Od@GRUp@KXQl@]|@[z@ABKVGN_@v@KVABKPIPQZQ\\A?Wd@]h@Yb@eCrDa@j@WZUVa@b@CD[Za@b@SRYXIF[XA@_@\\e@`@UNMJc@ZKH_@Va@Xe@Vg@ZOHSJm@\\a@R]LUJOH{Aj@A@y@VKBaB`@qCf@A?sANqALqBHw@@y@?aAAmAEe@Ca@Cw@GqBUwC_@gBSaEc@}BYiH{@}BYuEi@yFo@c@EmC[c@G}AQgEc@aBSc@GsEk@c@EgAOUCMAsAOWAo@EeBCmB@q@Bw@F_AHo@FKBm@Hm@JA?_Cb@qDn@kJdBUDoDp@MB{AXs@LsB^yAXgARyBTk@BM@M@Y@_BBQAw@CiBMkBWgAWQC_@OgDuAA?o@_@_BeAc@YUOiBiAUQYOs@e@s@a@ECYO_@S_Aa@w@[]K[Kg@Mo@Oi@Me@Ic@GWCA?m@GE?k@Eq@C_@@K?G?{@AA@oADQ@I@[B]DMBi@F_ARwA\\aAZq@XgBv@yAp@a@Pi@T]NsAn@w@\\s@Za@PYL{@`@uCnAgElBqB~@gDzAaC`AiGpCmGpCwCtAiF`CiEnB_@RgEnB]Ns@ZaJ|DwObHA?gDzA_@PsB|@_A`@aA\\aAZsAZe@Je@F[DA?QBO@e@D_@@e@@m@@k@Aa@ASAWAKAm@Gw@IkAOMCUC}HmAaAO[GwASk@I{@My@Ka@C[C]Aa@Ae@Ay@@O?U@u@De@Bg@Fy@Le@Hs@P[JWFGBm@RMDe@Rq@ZiAn@ULMJYP}@t@a@\\g@d@q@p@cAfAsGlH_DjDwBbCA@}BhCiAjAGH{@v@u@l@}@p@y@h@mAr@_Ab@k@V_A^aE`Bi@Rg@Ti@Ta@RYNc@XmA|@]Xu@n@WVq@x@{@fAQZm@|@w@pAkDvF[h@sBhD}CfFYd@yCzEyA~B_CzDYb@_@n@}BvDcA`BMT[`@GHA@s@~@w@|@cAz@y@p@URkA|@kAl@}At@}B|@gC`AeBp@cA`@gCbAa@PaA\\_DlAmCdAeA`@iA\\cAZiB`@iB`@eATeATi@L[HYFoAVaBb@mB`@i@NaCh@yEbAoAZuCp@gDt@QBSDOBMB_@JkAVe@Hw@JgAHA?k@@y@Bw@AU?YAs@AgACkD@kMQsNSwAAeDCM?oFIeAES?O?u@AO?wEEc@Aw@As@?SAO?S?O?w@As@AwJKQA}@?I?C?}ACIA{@AC?G?WAK?mAAu@?y@?y@@gCFI?Y@gADc@BU@M@_BFu@FsAHqR`Bc@Da@BeAJqCTc@Dc@BkGh@O@{It@K@cBNmK`AmCR{CX_BLcAHk@Fe@Hs@L_@JcKnCQFgHhBeCn@uBh@c@HkANe@De@BiAD{@@OA_BEq@E{@Im@KqAWmAY{@Y_Ac@}@_@uAs@eDkBsGsDa@YeDeBgCqAEEaB{@AAoBeAiAm@cB_AA?IGIEcB_AIEi@[s@_@yAu@}@e@eB}@?A}@_@g@S_A[w@Q{@O}AMu@GwAEg@BM?S@g@De@HQBaAPE@u@TE@C@o@TUJ{@`@EBo@\\m@`@i@\\a@\\aA~@g@l@oAbBc@j@e@p@aA`Bo@dAKNU^oA~AOTMR_AtAOPKNSV[\\i@h@]Z[VONoAz@w@b@g@Ra@N{@Z}@V}Cv@ODWFqEjAIB_B`@c@JeAVuA\\yA`@E@g@L_@HyD`AgFpAkCn@ODmDz@_@JA?iCn@A?kD|@c@JkCn@qBd@OBMBuF~AyA\\WDk@JQDe@Fa@DG@[@}@FQ?mABeBCo@Co@GgAKu@Kw@Mq@OMC[Ik@Om@Um@UcAc@CCcAe@{@m@gAu@aAs@_BsAcA{@kAeAcAy@}@u@u@c@w@e@a@WUMw@c@i@Wu@[s@YaA[aAWiAUu@Mo@IiAKs@E{@Em@?eACyECA?sFEsFEwBEoAAaFCcEGuEGC?wEEa@AeCAo@A_DASAwDE}ACwBIa@CcAGgBUi@IWEgCi@GA_AWiC}@]Oa@Qi@SkB_AaAi@QMWQa@Y_@Sy@k@o@k@cByA_B}AGEUUk@i@g@e@IKSQ]_@YWAAUWGEm@m@AAGEACyAuASQ{AuAeA}@w@k@c@WAAe@Wc@Ui@Wo@Ws@Ug@Mi@Mk@Ik@Gc@Ee@CCA_AAg@Ak@@U@e@BUBM@g@HyAVgPpCw@Na@HcAPgARoAV_APcAReCd@KBcBf@G@}Ap@cAh@q@`@e@\\ED]XA?OLe@b@c@b@IHWZUTU\\U\\OVy@hAg@t@k@~@_@f@GJ_@r@a@n@ADi@r@m@x@m@r@k@j@e@d@k@h@a@Vi@\\i@b@_@P[PqAn@oBbA{CbBcCpAi@VyAv@aAf@wIpEgBbAoB`AWL_@Ta@Rm@\\sAr@[N_Af@SJOHw@b@}C~A_CnAOHCBcAh@iG~CkB`AmAn@iAb@o@Vo@RWFWH{@N_@F_@Dq@Hq@Fk@@}@@w@?OAc@CUA]Ce@GC?_@Ei@K_@Gc@I]Gg@GIAGCy@MsAS?AA?gBYmCc@c@Is@KsGgAuCg@YGkB[a@GiB[kB[A?]GAAuASsAUEAa@ECAKAUC_@EA?e@Ee@Co@C}@AsAA}CBoEBiBBaGBeFDU?}SN]@sB?eBBg@@]?s@@uEF{BHqGV}BJyFReADA?cHXiEPo@BoCJwEPyCJsGVeJ^sCJsGVqERaBFG?E?kBFkBF_@@o@BK@{CLeBHI?gJ^eADeBHwCRkBRcCT_@BoLvA}En@uEl@sGv@kJjA{BRsEl@k@Hc@FaBTaH|@{Ft@_@DmLxAmC\\kM|A}Df@gPtBiFn@aI`A_Ef@{BXkBTaCX{BXaALyFr@}@J{@F{ADeAB}@A{@Em@C{@Ie@Im@Kq@Kw@Q}@Y{@WoAe@yEeBYKkCcAcCaAeAc@uAi@cBq@sAa@gA]w@SoAWiASeAK_BMgCGU?A?a@?u@?{BJ{CR_AHw@F{@FwD\\kGf@A?w@H{DZqBPeAHc@DuBRoBNw@FK@mANqANo@Hm@Ji@Jk@Ji@Jc@Ja@Hs@PmAZiA^k@NYLcA\\sAf@KDw@ZwAh@MFgCdAaC`AkBt@QFyCfAe@P_A^gAd@{PxGqEfBgBr@aC~@_@Na@PmAb@_A^eBp@aC~@kAd@a@NkFpBeA`@cBv@y@b@GBm@\\a@T[Ro@^]Va@TIFaAp@{AhA_@Vc@^_At@KHkAdA{AvAeAfA_BjBkAtAg@n@cDxDu@~@EDUXEDiBxB[^[\\EF[^{DvEGFSVGHo@t@uAzAs@t@qAlA_At@oAz@s@`@CBOFQJm@\\QH]P]Pg@TaA\\A@iA^[HQFG@IBQDMD}@Pi@Jo@Lo@Ho@FaAFsADkAD_FBc@?c@@cC@o@@oCBQ?wAFc@Ba@@}@HeAL_@FOBeARA?a@JSDu@Pq@TsAd@g@Pu@XqBz@aDzAcBv@cAd@a@P_@Ra@Po@XaAd@WJa@RIBaAd@{@`@iAh@oB~@{B|@GDaCx@y@XGB]Lg@LE@u@TgB`@IBc@HGB}@NA?WDIBSDm@HC@c@FMBm@HK@a@FYDIBgAN{@LI@a@DgANO@IB{@LyB`@g@F_BTgAPwFx@m@JgANOBk@Hm@HwB\\yARA?a@FA@mC^eAPc@Fc@Fa@FA?a@F}@J}CZgL~@a@BA?eBNa@Bq@Fi@Fc@DQBQ@E@[DE@k@HODOBm@LG@eAXGBs@Ri@RE@w@Zo@XYN_@Rq@`@m@`@IDs@h@cAz@q@t@y@x@CBo@t@w@bAcArASVUZoAfBkBrC}A|Ba@l@_AtAu@fAgA~A}BfDsA`Bk@r@KJcAjA_BzA_@Vm@f@OHy@h@eB|@C@cBp@eAZa@LwA`@A?e@Hi@Hm@HG?o@FoAFw@@a@?m@@o@Ci@COAoAM_AMmASqA[_AW_AYQGWI]Kq@SOCk@Se@Mg@Qi@M_AU_AUk@K_@G]Gc@G_BOA?sAGYAU?G?K?]AE?w@BI?g@Bg@B}@HaAJE@G@m@Jg@Jk@LYHWFeA\\i@RSHYJA@E@]Pk@Vo@\\o@`@SPUNGHEBe@^g@\\e@\\WRg@^m@d@QNEB_@XA@KHIHSNk@d@wAjA_Av@sAhAcA|@]Z]Va@X[RAB_Ap@YV_@Xm@d@yBfB}AnA]Xi@b@qAbA]XwC~ByApA}@t@]XURy@p@c@\\qB`BUPYTEBKHaBpAOJSLiAn@[Pa@Rg@Pm@V}@Vs@RuCt@_BVE@]Dc@FuAJs@DqAD}@?C?c@?m@AqACeAEcBK{BMuAIeDQqAGa@CKAmCOmBKiBKWAA?a@CYCgBIuAIsAIUAC?y@CeBE_A@qAF_AFcAJ_AL_AN_AT_ATu@XWJC@_Bt@kAl@[RC@m@^k@d@WRkA~@o@n@}@`AAB{@|@IHi@p@SXkAfBk@~@u@tAs@zAu@xAGLoAfCm@lAw@zAi@bAA@c@v@m@lAKTc@|@gA|B}@lBe@~@i@fAWd@Wd@IRo@jAYd@o@pA[n@CFc@|@u@xAMT[j@[n@]v@Ub@Yj@wApCuB`EWd@{@`Bu@xAS`@EHMVYd@SXOTU^]f@o@~@]f@i@r@i@r@ILa@b@WVKHe@b@e@\\CBy@l@c@Z]RA@[Re@X]PqAr@mB~@eBx@_CfA]PA@a@PULaBz@q@^g@ZSLED[To@d@QLQN]XYXIHYVeAfAc@d@k@p@UZi@t@m@z@W^i@~@k@`Ai@fAo@tA[x@a@fAQn@[hAg@fBUv@Ol@U`AQ|@ShAI`@G^YhBKx@M~@QrAYrCA@YpCE\\CRIn@Ij@Gd@Kv@QzAKlAKz@AFUrCQ~AGl@ADEj@Gd@SzBOtAGf@O~AMdAGh@CPC^CVQ`BIdAMxAIt@OhBQzAK~@c@`EIr@KbA[tCW~BEb@ALCTMdAs@dGI|@SxAQjAOt@Oz@_@jBQz@Qv@St@[fAi@nBOf@Md@O`@w@nB[p@ITeAlC?@ABi@vAeAzC_@dAI\\i@`B[lASz@ABU`AWpAAJG^Ox@UdBSvBOpBEv@C\\AVAVAVAd@GvCAz@?rA?tADdCFnBF|BJpBH|CPpEJpCHzBN`ELxCFdB@b@B`A?^FbD?x@AbBAh@?p@EjAE`BCj@EfACn@AFCv@Cb@WjGIdCK`D?DATMhDInCEbCC~BC|AAh@a@bRWpOAb@GbBAl@Ct@ALOfCM|AADE`@SfB]pBa@xBADI^GVi@bCW~@IXGNQj@Sf@KZO`@IPM\\EHSb@O\\[n@g@~@MZYf@k@bAq@fAW\\m@z@c@h@]`@m@h@e@d@OLu@n@k@d@{@t@[PSHSJc@PIDEBUJGDa@NC?y@ZEBa@Na@NmE~AeBn@cA`@a@NcA^C@gEbBa@PcA`@IB_@PYLaAd@a@P]PC@g@XWN?@kAt@s@f@]Xa@Zc@^MNGDy@z@SRIHY\\A@[b@q@z@]f@]h@]h@OVWf@U`@]r@CFa@|@O\\EJSh@GNWr@Yz@Sj@Qj@EH_@lAIXcBjFOd@O^IZM`@Qj@Oj@W|@Y`AADQp@Qd@Ul@Sh@c@tAy@xB{@xBeA`CaAtBs@rACHgBzCm@`AyAvBWb@s@|@gB~BW\\uBtCGHQVGFSXuDbFwAnBcArAUXwAfBGD{@nAaBvBcAnAcApAk@v@o@|@a@j@}@pAy@fAyBxCo@v@aBxBs@bAc@p@KRSZ{@zAU`@[n@u@~A_@v@a@dAWt@Up@Qf@CHSb@Qf@Qb@Wv@Qf@Of@Qd@Ql@Oh@Sp@WlAW`AQz@K|@Ox@QdAG\\MbAKd@Ih@Gb@AHG`@Ox@Kr@Ip@Kz@Iz@Kz@SvAQlAWlB?DYhCGf@MbAIr@[hCq@`Gw@dHUpBUrBgAbJu@jGgApI]pC_@vCKx@YzB]`DQzAAJIn@EZQzAa@`Cm@dD_@tB_@lBa@zAc@bBi@fBK^Qf@}@xBy@hB{AhCu@nAKL}BfDEFUVKNMLY\\GFUTKLEDq@l@cAz@mA~@KFYRg@X]Ty@f@A?_@T{@^EDIDmAd@UH_@LKBaAXA?SFKBa@J]HA@I@wBl@mCt@YHiAXaBd@i@Po@TgAb@wAr@}BvAg@\\SNc@Zw@n@A@]Z{@t@q@t@q@x@a@h@OV[h@]t@CBm@lAABg@dA[j@OZw@tAWd@GJOXq@hAEHg@z@Yh@i@`A_@n@OV]j@CBk@x@GJg@r@_@l@EHWd@KPYj@[n@[l@KT_@p@]j@Ub@S\\Yn@]l@a@x@m@nA_DrGc@t@_A|A]h@]f@k@t@QRc@f@m@r@CB[\\A@Y\\STc@b@_@\\A?]XCDg@ZSLQJg@Tc@Re@Pk@Nu@Pk@JaANaAL{ALy@Ls@H[DG@kBRy@HgAJm@HK@WHeAV{Aj@MFqAn@o@^aAn@g@XWRs@f@g@^g@`@u@n@WT]`@_@b@[`@WXk@~@y@|AWf@]r@[r@cAvBa@bA]bAc@vAW|@[pAGRk@rBg@bBi@jBa@zAW|@IZ_@pAAF_@zAMn@yArFo@~AELa@lAu@pBk@~@Q\\Yh@i@bAa@p@i@t@CDy@jAq@bA{@fAOPQR_@j@i@r@eFlGY\\Y^KLcE`Fw@dAu@dAGFWZUZUXs@`AKLo@v@GFW\\]d@m@v@iB~Bg@n@a@f@yAhBMPqAbBSVm@t@a@j@m@t@IJ_AjAQVqA`B{EhGqA`BSVa@d@]b@k@t@CBa@h@Y\\MPC@IJcDfEILk@r@W\\k@l@gAlAkAjAUR]ZMJIHaAz@WTEDOLIFcBnAWREDYR{BbBuA`A_@VIDe@Zw@h@}@l@A@u@h@{@j@e@^a@Vu@h@c@Z}@j@g@Xe@Xg@V{@`@a@NYL{@\\i@Pg@PA?i@P}@VcATm@Nq@Nk@HwANy@FE?}@Fg@Bc@D[ByAHeCNeAHe@DwAJs@Hw@JuAPE@uB`@_BZ{Ab@iAZKDoBr@KDc@NA@_A^u@\\m@Zg@T_B|@_Aj@gAp@u@f@q@d@a@Ze@`@a@ZA@g@`@gA~@u@p@u@r@c@b@eAdA_EtE{DpEeDtDgCxCiCxCOPqCdDsC`D{CjDyFxGgAnAsA|As@x@UVmBzBoB|BwErFKHw@|@s@v@sA|AqAbBsAnBk@|@mAnBc@~@qAlCk@rA_@x@_AdC[z@Qj@k@pBg@nBGT]vAs@lDSnAUrAM|@QxAWvBGd@I|@Gf@Gz@OhBM|BKxCE`CCjBAfC?`DCtG?pDAdB?tBAjGAjAAhDAxD?@Ar@?X?fD?|@?vBAtD?DCrCAxBAvAAxCCxCCzCCx@EzAAXEz@KtBARMbCCf@Gz@QjBYlCGn@?@c@`DSpAYbB_@rBET[xA[rAe@dBY`AeApDeE~LWv@M\\"
                     },
                     "start_location" : {
                        "lat" : 44.4237691,
                        "lng" : -79.6531476
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "75.1 km",
                        "value" : 75112
                     },
                     "duration" : {
                        "text" : "46 mins",
                        "value" : 2747
                     },
                     "end_location" : {
                        "lat" : 45.9860439,
                        "lng" : -80.57117119999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-69 N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "gjitG~~_hNqBxFs@jBSh@Qj@e@tAsHtTm@jBSj@iBlFuA`EO`@cLrXkClFiE|GmBbC]\\iAlAaA`AoBjBk@f@ML{DnD]\\wClCgIrHIHeBxAgAbA[Z]\\[^[^W`@A?W`@KNOR[`@SXUXeAjAQVa@l@sCrCCBsBjB]Xa@^u@x@{@z@uA`Bs@~@wAlBSXaH~J_JpMOT[`@iBjCkFxHoAfBY`@u@dAeBfC_IdLY`@yB~CuCbEc@n@oC|Dg@t@s@dAoAhBwArBiG~IcAxAY`@A@mAdBKN{AzB[b@_AtAA@sGjJY`@g@r@g@t@Y`@s@bAaAvAaAvAaAvAMPKNMPmAhBiBjCKNcAvAiBhCKNcAvAW^u@fAg@r@c@p@_DxEaCjD{AzBCDiAnBYd@GJgCpEYh@cJjPWd@_BvCYd@{K`ScHfM_BtCWd@aBvCWd@aElHo@jAwBxDi@`AwDzGyB|DwBzDcHdMo@jA{EtI{AlCcHdMkAvB{DjHWd@OXiB~CaA`BA@yBjD{BfDm@~@Y`@iF~HaCnDmAjBy@jAqHbL{CrEYb@Yb@aCpD{CrE{CtEmAhBmAhBYb@mAhBiC|DeA|AkIfMoFbIm@x@yIfNCDU\\yHdLY`@s@dAcCnDYb@qBvCcA|AuJ|NeA|AcG`JoEzGs@dAgBlCYb@m@~@oFdIs@dAoEzGs@dAaCpDsH~KYb@Yb@aLtPcAzAYb@aGbJmAhBYb@Yb@{CrEcGbJa@r@a@p@cCtDg@t@GHY`@iGfJYb@MP{AxBINeBfCYb@QVGHY`@KPwEdHY`@W`@Yb@q@bAOTILeBfCk@z@_C~DIJOVWb@Wb@A@mA`CGJCFKRGRYl@y@nBc@dAELSf@Wp@KTWr@Sh@u@tBSl@ABSh@aBpEk@|AWz@Sh@i@rAo@fBWn@c@nAWp@Ob@Sh@Sh@mCpHaBlE{@~BCFc@lACD}BlG{@~B}@~B}@`Ce@pASj@oAhDaAlCgA|CSh@q@nBk@|ASh@{@~BqApDgB~E?@kAbD[t@Up@g@`BM^qBfHIZs@jCOn@A@qFdSQp@Qj@{CbLiDrMQl@s@jCcAxDmApEiBbHOj@K`@?Be@bBOl@]rAUz@a@xA[lAELI^g@fBQp@YfAa@zAELCJGRCJ[lA]nAIVKd@Of@Qp@W~@Ux@M`@I\\Uz@W|@EPOl@Y~@U|@U|@YbAa@|Ac@~A]nA]pAUz@CLSp@Mf@W~@_@vAENU|@Qh@AHY~@Sx@ABK^IZYbASt@Kb@a@zAW~@_@zA]pAMh@a@zAMf@Qr@Qp@a@bBSbASdAS`ASfAQ`AYdBYbBa@fC]dB_@`Bw@bCYt@g@tAYl@Q`@o@tAS`@Ub@GNOZ}A~CmAfCqAhCUf@m@lAA@e@`As@xAA?oAjCWl@Wj@O^q@hBADMf@Ql@Qn@Sx@YlA?@Mb@CLa@hCKp@U~Ai@zDKt@_ApFOn@?@{@~C[|@Ul@Yr@qAtCUd@ADoB`DKN[`@gAzA]`@mBdC[`@u@`A[`@w@bAoAbBa@j@eBxB[`@iB~BoD~EcBpB[^A@QTaAfAe@h@QPwCnCoCfC}AzA{@v@{ArA]\\qFdFoBfB_A|@?@cDvCON]ZA?sClC]\\OLsCjCm@j@IHSRg@b@SPeAbAWTsBhBIH?@]^oBdBo@j@a@\\iA`Ao@j@m@j@{@v@]ZsAlAi@d@C@{@v@c@\\SRaCtBQN]Zk@d@?@GDIF}@r@i@d@A?q@h@u@l@eAz@{D`Dw@p@o@f@yAnAKHw@f@]Re@Vc@TUJw@^MD]LC@k@PuAZm@Lk@J}@PE@_APOBu@NI@YFeAR}@PG@I@}@P]FC@k@Ja@H[Fc@Hk@L}@Pg@J]FG@QD_APWDgEr@iB\\oB^c@HkCf@gARaAReAT}Cl@aARa@FgARgATa@HOB}Ab@c@LuAj@q@Za@Ta@Rw@b@_@VIFaAr@w@r@s@n@_A~@IF}AxAyAtAcB|AoBhBEDA@URGFmBdBKHaA`AoCfCoBhBeBbB}AvA{AvAu@p@UTA@EDWRGDWTuBbB_BlAu@f@eAl@iBdAQHOFs@^k@VaBp@aCx@gA\\}@V{Ct@C?]JC@k@LmCp@cCl@_@HsEhAYFgHdB[H_E`AuD|@mCn@oAZeAVE@[HmAXoBf@u@PoAZYFeAVIBYFeAVa@JiAV]JkAXkAX_Cj@c@Hq@PWFkCl@oEdAeATm@NuBf@m@Nc@La@Je@N_Bh@C@eAd@]Ra@Rk@^SLOJMLm@d@ONURo@l@a@`@]^WZy@bAoAfBgBjCQVYb@[b@mAhBY`@gBlCY`@oAhBYb@Yb@W^A@Yb@Yb@wDvFmAlBEFSZcCnDmAhB}CpE{A|BYb@s@dAu@dAwIpMo@~@{CrEYb@Yb@Y`@wDvFYb@ORILYb@wDvFgBjCYb@sIjMkErGsJrNaCpD[`@eG`JcAxAABY`@Yb@SViCxDeHlKm@|@oN~ScCnDYb@Y`@s@fAY`@mAhBgBjCoDjFg@p@IJc@j@QVEDUXIJw@~@QR]\\CDg@h@sApAGH_Az@u@l@kA|@_@XMJi@^c@Xk@\\m@^kAn@WLqAp@mB`AeB|@cErBa@RaAf@cCnAe@Vu@^cBx@a@Ra@RmJvEmKlF_@RcHlDsIhEaAf@iIdEmHnDmB`Aw@^u@`@e@Rq@Xw@Z_Bx@sBbAo@\\mAl@aAf@w@`@GBeAf@u@^cAh@mAl@}@d@uBbAwAr@iCpAcCnAiCnA{@b@OHa@RC@gAh@WLWLGDg@VkB~@}@b@{DnBkAl@a@ReAh@gCnAuDlB}@b@OFy@b@eB|@mCrA_Bv@}Ax@e@TeBz@qCtAs@^aAf@eB|@uCzAaB~@KFa@Ty@d@gB`Ao@ZoCzA}@f@qGlDaLfGqEbCuBjAIFw@`@sBjAoAr@A?]TaB~@_HtDu@b@}CbBQHwBlAwJnFyHfE}DvBsFzC}@d@o@^}DtBWNcGdDcB~@aAh@g@XsBhAy@b@gDhB}@f@yC`B{F|CwAv@_@RaAh@WL_DdBYNu@b@m@Zy@d@o@^g@ZsQvJiAl@oAr@kAl@cDfBaAh@cCrAgHxDSJqCxAmAp@cG`DaAf@WNGBYN{C`Bw@b@u@^e@TA@WJEB]Ni@Tm@T}@\\u@Ti@Na@LODa@Jk@NC?[HE@WDSDOD]FWDI@]FUDE?]DG@A?i@Fi@Dc@D]BWBy@FoCPG@yCRqBLkGd@k@Hu@DqAJkBNyALi@DqAJe@D]DUBYDQBSDOBMBQDYHYHQFODWHOFSHSHQHSHOFOHUJWNMHSJSLMHOJSN_@Zc@ZGF_@\\]\\[ZYZA?Y\\A@SVGHORSVQXORQXQVQ\\U^QZSb@Uf@Ud@[v@Sd@Ob@Sh@K\\Of@Of@Oh@Kf@Mb@Kd@Kf@Id@Id@I`@Ij@G`@Gd@EXCR?@C\\CPCVCX?FGv@Gx@KxACh@Er@Gt@Q`Dk@jJO`CEp@S|CWtEO`CEp@Et@Cf@C\\KxAI`AIt@Gn@Mz@CTE^Ib@Il@Kf@Kh@Mh@]|A]pACH]dAYx@[x@Sj@]v@_@r@Wh@a@r@_@n@[f@_@h@Y`@MP{@dAwAdB{@bAy@bA[^KLeAnAiAtAaAjA_AhAkAzACBWZ[^GHST[`@C@kB|BuAbBqA~Aa@d@mAxA[`@oB`Ci@n@mGtHWZw@`ASTGH_AhAg@n@m@p@YZWXUT[VWTUP[T]Ry@b@[PYLm@XOFs@\\_@Ra@Pa@ReD|AcAd@a@RA@]NmCpA{Ar@w@\\sBbAgAh@aChAcChAuAn@cAd@iBz@aCfAkDbBs@ZcBx@gBx@w@^gD|AULKDgD|AWLkB|@a@PeBx@uCtAuAn@cAf@e@Ti@XQHqB`AcAd@[NEB_@Py@^gAd@e@TSHcGrCGB_@RaDzAmEvB_@PeBx@ULsAn@GBc@RgBx@cElBaAb@_@Pc@ReClAcD|AA?cBx@a@RcBx@UJk@Xa@PgD|AiAh@cGrCa@PmCnAmErBSJw@^wBbAkGtCsJrEaAb@sB~@u@Vk@PYHc@JmD~@a@J{A`@}ElAeAXuIvB}MhDMD}@T{UhGkCp@ODSDiItBkItB{Ct@sKlCuA\\wDbAwBh@cFrAkCr@A?kD~@_B`@I@a@LoG~AaIpBkCp@{@RsCt@c@LmD|@c@LA?eCl@A@eAVwFtAcAVkCp@mD|@a@Jc@Ju@RkFrAWFu@Ra@JGBkFrAc@Lc@JoEjAwDbAqCp@c@Lg@L]Da@HeAPu@FS@c@Bq@@gA?m@Am@CA?a@Gc@EI?YESCs@Ka@IEAiAYYGoCs@oCu@YGa@Ma@Kc@KQGOE{Aa@MCcAYc@Ma@KOEwAa@c@MgBe@UGwCy@iBg@cAYa@Mc@Ma@Ma@KKE{Aa@c@K]KqDeAa@MMEUGa@MeAYw@SME}C{@OEa@IQEQCc@Ia@EA?[CEAc@AUAM?o@@i@@e@DYBe@FWD_@HA@mA\\}ClAqBz@sBx@eIfDwB~@aC`AeBt@a@NoH~CcA`@a@Pa@P_@Na@Pa@PiDvAeBr@a@PeCdAcA`@aDrAi@Ta@PoHzCa@PcA`@a@PgDvAcBr@c@Pa@PoAj@k@TIDa@NYLg@LC@e@JQBQDYDE?UBW?Y@I?_@?e@Ci@ESEOAm@Mk@MiCy@GCw@Us@UUG[IUGq@MA?MAOCSC]EE?QCQAc@C}ADsBPk@Da@DA?wA^wAd@}An@kFjCa@RuBdAoAr@a@Pm@XiB~@qAl@aAd@OHq@^cBz@k@ZUJkCrAiBhAo@b@_An@yBvAeCfB]VSNkAx@_@VuBzAgBlAmAz@o@d@_BhA_@VWReBjAaBhA}CtBIFu@d@QJy@^yA^_APo@JA?a@Du@DwABc@C_EWWCc@C{CU}AMc@CqE]cF]oCQkBOc@CeAIc@Cc@Ec@CaAIi@Ec@E{BQQAc@COA{AO_@CuBGg@AkAAGKECOEw@EQCeAGuBOiDWc@CEAcBKkBMyAKQAgAGgAISAuAKc@EiBMoCSm@EaBOgAIy@IMAqDWgAIwBOUCgAGc@EsDUaCQK?c@EkBMgAIc@CqAIYCmCSoCSeBME?iBOc@CsDW}@Ik@CgAGkBMwAI{AMuE]mBMa@EyD[aBSMC}BWe@ImAQ}Bm@GAcBi@gAa@kAe@{Aq@eCkAKCw@_@eBu@iAg@YMeAg@]OwDgBgF}BUK{BeAmAg@cBs@[OiAe@aAc@c@QsAq@q@WqAk@wAe@c@OyCaAwA[e@KgCo@kBg@_@GgAQg@I]EcCYIAkBUIAcCQEA]AkBIc@C_@AaBK"
                     },
                     "start_location" : {
                        "lat" : 45.4366808,
                        "lng" : -80.1228842
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "14.9 km",
                        "value" : 14859
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 541
                     },
                     "end_location" : {
                        "lat" : 46.0995522,
                        "lng" : -80.66430010000001
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-69 N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wstwGxpwjN_PRA?eADsCVgDXO@kGp@uEf@oMvAkLnAgALgAJyDb@mCXmCXoCZmCXmCZ}QnBg@H_@DG@[DK@uC`@M@q@HIBE?E@m@JkB^wCp@mBh@gBh@{@\\oBr@{Ap@kAf@eAh@wAp@_Ah@a@T_@Ry@d@oDhCgF|DIFwEzD}@t@kAbAc@^a@\\]V?@_@X]Zi@b@yCdC{@t@_@Z{@t@{AnAOL_@Z{@t@EDEBqIdHi@d@iExDsGrFaAx@eEpEyBbC_D|DaGtH{@fAKNyAnBu@`Am@v@mBbCqAbBmBbCiCfDY`@[`@u@`Aw@`AUZIJIJKNmBdC{@fAuAdBcGrH_IbKiJvLsAbBY`@aEhFY^UXuFpHiG`IoIxKqCpDmBjCqA~Aw@`AsAbBgCbD[`@i@n@i@p@w@`Aw@~@[^[`@[^KJOR]\\]\\[\\y@|@]\\[^C@YZg@f@o@n@]\\]Z]\\[\\]Z]\\]\\]ZEFs@r@]\\]ZKJQP]\\]Zk@j@MLMLONkAlAKJ]Z{@x@]\\]Z]\\m@j@eSdSeAjAEB[\\]\\qCvCuDdDeAfAmAhAUT}B|Bk@j@gBfBA@w@x@yAvASRIH[\\{@x@{@z@uCpC_A|@uAzAa@d@a@f@STSVORIJs@|@_@f@c@l@OVg@z@ILCFKNa@p@OT?@[f@}AtCyB|DyB~Do@jAILMVILABaCfEaCdEGLOVEFCDaA~AILg@x@[d@{@tAGFQXgAvAGHABk@x@c@n@Yb@QR}AlBaBhBqD`E?@IHMNEDuDvD_CxBOJ?@IHoAfAKHUNqAfAkA~@y@j@A@IFs@h@_@VIFSNA?IFA@sAz@sMrImDxBA?KFSL?@KDeF`D[RSLA@IFaKvGSLA@IFUNiBlAuEzCKFiAt@i@ZA@IFULIFuBnAKHcAl@qD`C?@KFGBkAx@KFSL?@KF_DhBmCfBUN_@TGBKHi@\\a@VKFq@b@uAv@aAb@ULsAn@KDSHA?[NiA`@KDSHA@mDrA"
                     },
                     "start_location" : {
                        "lat" : 45.9860439,
                        "lng" : -80.57117119999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 585
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 35
                     },
                     "end_location" : {
                        "lat" : 46.1045398,
                        "lng" : -80.6638449
                     },
                     "html_instructions" : "Take the \u003cb\u003eON-64\u003c/b\u003e ramp to \u003cb\u003eCh. Doust Lake Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAlban /\u003cwbr/\u003e Noëlville\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSturgeon Fls\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "eyjxGzvikNSCE?ODuAb@SBa@HA?C@k@Bk@Bk@A]E[GUGUGYOa@UOKSMKIyCyBSKWGSCG?O@WBUDWHe@PuBx@"
                     },
                     "start_location" : {
                        "lat" : 46.0995522,
                        "lng" : -80.66430010000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.9 km",
                        "value" : 4914
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 256
                     },
                     "end_location" : {
                        "lat" : 46.1034,
                        "lng" : -80.6011656
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eON-64 S\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kxkxG~sikNImAAUASCk@E_B?iA@cA@q@ASAS@yD?aA?wA?K?wE?K?yAAaAGqACi@Gu@AOC[Gk@Is@QeA?EScA]aBIUsAeFKa@CKOm@ESWkA?CQ{@SoA?CQkAKoAKuBIyB?GEwA?kA?i@@s@@KD{A?CL}BJmAfAcMFq@NcBFs@NcBFq@NeBh@{FVwCNeBNcBBSTcCJcAB_@N{BFy@FaBBgAB{@@W@uB?KAgC@u@?_B@oEAgG?}DA}F?aGAoE?{C?[?oE?s@?[AkA?gB?{C?{C?YAgF?{C?aC@qB@wA?Y?kP?{C?aG?{CAcGAqM?QBiC?i@B}ABgA?GBi@@[@WBg@Dk@Dg@JeA@KD]Hu@Hq@RcB~B}Ob@uC"
                     },
                     "start_location" : {
                        "lat" : 46.1045398,
                        "lng" : -80.6638449
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "9.4 km",
                        "value" : 9382
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 514
                     },
                     "end_location" : {
                        "lat" : 46.0325032,
                        "lng" : -80.60020969999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eON-607 S\u003c/b\u003e (signs for \u003cb\u003eFrench Riv Sta\u003c/b\u003e)",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gqkxGhl}jN`Ch@VD^B`@BNAXAX?ZEXGJCb@OTI`@QbAa@`@QvB}@n@Y`@Q`@ObAc@bAc@`@OVM`@OpAg@\\K`@MXK`Cg@xAWb@IbAOb@Ep@E|AEbBCpA?|HAD?vE@fA?b@?jB?nC@jB?b@?jB?fA?b@?nC?zF?b@?b@?`@?b@?`C?xB?jB@b@?b@?jB@zF@bE@zJ?vE?rD?b@?rC@z@Bt@Dz@Fb@JD@^Nd@T\\XhAlAX^R\\Xl@N^J`@BJF\\Jn@Jt@|@zKHz@NdBz@rKFp@NdBFp@JjA?DD\\BRBJJd@DNFPXn@n@jAXd@Vd@Vd@fApBXf@n@jAn@jAn@hA@@Vb@Xd@Xb@R\\JLJNHFXZd@`@ZP~@j@JFv@\\@?VJ^LTHTF@?RBVBXBH?T@BAN?RAfAIb@Cb@EjF]jBMnCS`@ChAI`@CfAI`BKl@EfAIb@CdAIdAI@?rBMv@Ef@Af@ALAp@Bd@FD@^F@?b@JdATH@PBF@RBNAPAPCHAVGNCt@U`@MPEPEHCVEBAZEB?b@CBAbABb@@F?R?F?F?fAEPAHALCv@QNEPIpAm@PMLK^a@p@kAh@u@XWLMt@[|By@hEeBb@Ub@WBA^Yt@{@hDeEZa@t@_Av@aAZ_@jJiLZ_@Za@xFeHfDcEp@y@LUNYFQFSHa@Hg@LgAFe@DYJe@DUH]Vo@Vc@R_@V_@TY`@c@b@a@^[ZS^Wd@[x@k@^Wb@[v@k@@A\\[ZUb@e@V[h@u@JQ`A}ArB}CfC}DlAmBr@eAFILKLKHG@?LENETCX?XDPFLHRLLJDDTZJNFHbCnFdDbG^p@zBjEhAnCbB|DtCvE"
                     },
                     "start_location" : {
                        "lat" : 46.1034,
                        "lng" : -80.6011656
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 497
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 40
                     },
                     "end_location" : {
                        "lat" : 46.030245,
                        "lng" : -80.59486029999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cv}wGhf}jNXa@Za@rAkBRWt@cABGT]@C@APa@BGPe@\\yABK^oCHg@Ly@@IHe@Hg@@IRwAF]BS@GTyA"
                     },
                     "start_location" : {
                        "lat" : 46.0325032,
                        "lng" : -80.60020969999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 300
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 46.0281698,
                        "lng" : -80.5923689
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eSettlers Rd\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "_h}wGzd|jNbBwBrAeBv@aAZa@NU`AmATYDEZa@FI"
                     },
                     "start_location" : {
                        "lat" : 46.030245,
                        "lng" : -80.59486029999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "53 m",
                        "value" : 53
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 46.0282,
                        "lng" : -80.59294109999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "a{|wGhu{jNNb@BP?F?FAFADEHGHGH"
                     },
                     "start_location" : {
                        "lat" : 46.0281698,
                        "lng" : -80.5923689
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "73.4 km",
                  "value" : 73437
               },
               "duration" : {
                  "text" : "55 mins",
                  "value" : 3325
               },
               "end_address" : "Greater Sudbury, ON, Canada",
               "end_location" : {
                  "lat" : 46.4917321,
                  "lng" : -80.993008
               },
               "start_address" : "20112 ON-69, French River, ON P0M 1A0, Canada",
               "start_location" : {
                  "lat" : 46.0282,
                  "lng" : -80.59294109999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "53 m",
                        "value" : 53
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 19
                     },
                     "end_location" : {
                        "lat" : 46.0281698,
                        "lng" : -80.5923689
                     },
                     "html_instructions" : "Head \u003cb\u003esoutheast\u003c/b\u003e toward \u003cb\u003eSettlers Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "g{|wGzx{jNFIFIDI@E@G?G?GCQOc@"
                     },
                     "start_location" : {
                        "lat" : 46.0282,
                        "lng" : -80.59294109999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 300
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 29
                     },
                     "end_location" : {
                        "lat" : 46.030245,
                        "lng" : -80.59486029999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSettlers Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "a{|wGhu{jNGH[`@EDUXaAlAOT[`@w@`AsAdBcBvB"
                     },
                     "start_location" : {
                        "lat" : 46.0281698,
                        "lng" : -80.5923689
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 497
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 39
                     },
                     "end_location" : {
                        "lat" : 46.0325032,
                        "lng" : -80.60020969999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "_h}wGzd|jNUxAAFCRG\\SvAAHIf@Id@AHMx@If@_@nCCJ]xAQd@CFQ`@A@ABU\\CFu@bASVsAjB[`@Y`@"
                     },
                     "start_location" : {
                        "lat" : 46.030245,
                        "lng" : -80.59486029999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "9.4 km",
                        "value" : 9382
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 521
                     },
                     "end_location" : {
                        "lat" : 46.1034,
                        "lng" : -80.6011656
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eON-607 N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "cv}wGhf}jNuCwEcB}DiAoC{BkE_@q@eDcGcCoFGIKOU[EEMKSMMIQGYEY?UBODMDA?IFMJMJGHs@dAmAlBgC|DsB|CaA|AKPi@t@WZc@d@[T]ZA@w@j@c@Z_@Vy@j@e@Z_@V[R_@Zc@`@a@b@UXW^S^Wb@Wn@I\\ETKd@EXGd@MfAIf@I`@GRGPOXMTq@x@gDbEyFdH[`@[^kJhL[^w@`Au@~@[`@iDdEu@z@_@XC@c@Vc@TiEdB}Bx@u@ZMLYVi@t@q@jA_@`@MJQLqAl@QHODw@PMBI@Q@gADG?G?S?G?c@AcACC@c@BC?[DC@WDIBQDQDa@Lu@TOBWFI@QBQ@O@SCGAQCIAeAUc@KA?_@GEAe@Gq@CM@g@@g@@w@DsBLA?eAHeAHc@BgAHm@DaBJgAHa@BiAHa@BoCRkBLkF\\c@Dc@BgAHS@O?C@UAI?YCWCSCA?UGUI_@MWKA?w@]KG_Ak@[Qe@a@Y[IGKOKMS]Yc@Ye@Wc@AAo@iAo@kAo@kAYg@gAqBWe@We@Ye@o@kAYo@GQEOKe@CKCSE]?EKkAGq@OeBGq@{@sKOeBI{@}@{KKu@Ko@G]CKKa@O_@Ym@S]Y_@iAmA]Ye@U_@OEAc@K{@Gu@E{@CsCAc@?sD?wE?{J?cEA{FAkBAc@?c@?kBAyB?aC?c@?a@?c@?c@?{F?oC?c@?gA?kB?c@?kB?oCAkB?c@?gA?wEAE?}H@qA?cBB}ADq@Dc@DcANc@HyAVaCf@YJa@L]JqAf@a@NWLa@NcAb@cAb@a@Na@Po@XwB|@a@PcA`@a@PUHc@NKBYF[DY?Y@O@a@C_@CWEaCi@"
                     },
                     "start_location" : {
                        "lat" : 46.0325032,
                        "lng" : -80.60020969999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.7 km",
                        "value" : 4723
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 242
                     },
                     "end_location" : {
                        "lat" : 46.1046624,
                        "lng" : -80.66138239999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eON-64 N\u003c/b\u003e (signs for \u003cb\u003eAlban\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gqkxGhl}jNc@tC_C|OSbBIp@It@E\\AJKdAEf@Ej@Cf@AVAZCh@?FCfAC|A?h@ChC?P@pM@bG?zC?`G?zC?jP?XAvAApB?`C?zC@fF?X?zC?zC?fB@jA?Z?r@?nE?Z?zC@nE?`G@|F?|D@fGAnE?~AAt@@fC?JAtBAVCz@CfAG`BGx@OzBC^KbAUbCCRObBOdBWvCi@zFOdBGp@ObBGr@ObBGp@gAbMKlAM|B?BEzAAJAr@?h@?jADvA?FHxBJtBJnAPjA?BRnAPz@?BVjADRNl@BJJ`@rAdFHT\\`BRbA?DPdAHr@Fj@BZ@NFt@Bh@FpA@`A?xA?J?vE?J?vA?`AAxD"
                     },
                     "start_location" : {
                        "lat" : 46.1034,
                        "lng" : -80.6011656
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1184
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 48
                     },
                     "end_location" : {
                        "lat" : 46.1117073,
                        "lng" : -80.67029839999999
                     },
                     "html_instructions" : "Take the \u003cb\u003eON-69 N\u003c/b\u003e ramp to \u003cb\u003eSudbury\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "cykxGrdikNGPCPEj@ChA?hA@nAF~A@x@@D?`AAf@Gv@EbBW~AQn@GXYv@Uh@u@hAA@a@d@i@b@cAl@KDa@REB_@PuAr@c@PEBi@XcAf@kAd@eAd@MFiFvBa@P}@\\iAb@GB{@\\]NC@a@Pa@T_@T"
                     },
                     "start_location" : {
                        "lat" : 46.1046624,
                        "lng" : -80.66138239999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "48.7 km",
                        "value" : 48729
                     },
                     "duration" : {
                        "text" : "27 mins",
                        "value" : 1643
                     },
                     "end_location" : {
                        "lat" : 46.4358488,
                        "lng" : -80.96983940000001
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-69\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "eemxGj|jkNmFtB{NzFwB~@}@b@}@d@y@f@oAt@y@j@kAz@cBrAKJmB`Bg@`@gI`H]ZMJQL{ApA]XyBlB{BjB]XyCfCaEjDgIbHqHlGyDbDiErDwD`DmRhP_@X{ApAsFvEwDbDsC`CaCrB{@r@e@^a@^e@`@gA~@{@r@y@r@q@j@g@d@q@n@UTOLQPQRc@d@ONABa@b@OPOPq@v@OTa@h@_@d@W^W^QVORMRMR_@l@[h@QV]l@KRMVi@`AcB|C{@`BcCrEsAfC_AbBe@v@]j@c@r@{@lA_@f@m@x@_@d@QTq@v@c@f@]b@e@b@OPQNSRONQPOLe@`@QPQNw@n@e@\\QN]Vo@b@e@Xc@XUNQHy@d@c@T[Nc@TUJUJ_A`@_@Ne@Rk@ToAf@g@T{Al@{D~Ai@RgBt@}B~@qElBa@NeBt@wF~By@\\aSfIcBr@[LmAd@kA`@o@Ry@Tg@NI@gAVk@Jk@LmAPYDy@JYD}@F_AHgHd@[@mAHsAHkCPgCNsCRiAHU@UBmG^{BPe@DeALUB_ANgB\\{@PUFyA^oA^gA`@]Lg@Ry@\\w@^A?sAr@w@b@g@Zu@d@g@ZQLi@^_@Xe@^e@\\u@p@u@p@[X}@z@]`@u@x@s@x@KLST_@d@_@f@ORSX[b@a@l@{@rAa@l@{@|Au@rAc@|@EF[p@Yl@g@jAYl@Un@MXWp@g@tAWv@o@jBa@tASr@gK|^c@`BcCrIAFu@|Bw@dCk@jBeAzCWr@cBlEkCnG_@x@mAhCc@~@{@fB_@v@sBdEWf@cAvBaDtGsApCu@|AyEdKUf@m@pAUf@Wf@oBhEUf@qBjEm@nAUf@cAxBMZcAxBo@tAeCrFyP`_@kEjJk@nAaApBcB|CkCbEaAtAo@x@OR_@b@o@t@iAnAo@p@e@b@u@n@eA~@m@d@]XkAv@w@h@y@h@y@b@q@\\IF{@`@{@b@g@RaA^w@Xi@Pg@NSFUFSFk@N{@RWDSDi@J[Do@Jo@H{APaAHeADkAHkBF}DTkFV}@DoJd@kBJsBJyCLeI`@{AHqALuAP_ALi@J{@NwAZqA\\yDpAiCfAuDpBWNq@b@aBfAkA|@mB~AcA`Au@t@QPSRMNgAlA_@d@QROPMRWZIH_@h@o@~@QTMRKN_@n@y@tAILU`@eB~Cm@hAaErHo@lAyExIWd@sZ`k@oEfI{IjPWf@cDbG}BhEyFlKuBzD}CzFWf@OVeAnBABKPm@hAKPi@bAa@r@IJOVGLcBhCa@j@i@t@GJ[`@e@j@m@t@eAhAa@b@{AvAIHUTcBxAsAbAOLQLOJ[RQJe@\\m@\\OHQJQJe@VUJOHC@QJoAj@SFEB}@\\YJUHq@TqA^MDE@uA\\QDUFUDKBA?a@FMDUBUDE@_ALMBK@WBc@D{ANM@gADq@@k@?}A?mA?{@Ec@A[Ai@EeAIIAoAMoAS}AWiBa@SE}@WkA_@c@OOEcBq@_Aa@gAg@kBeAkC}AyKsGa@WoBkAkF}C{@g@iQkKoAu@qDwBMISM_B_AcI{ESKeBeAmAq@{@c@c@SYMk@Ui@SOGg@O}@Yo@QSEc@KaAQQC_BSmAKeAEeBEgGKWAcFK{@AyCGY?KAa@AmCEuAA}A@qADy@HsANyAT}@T{@VaAZ{@\\KFYL_Ab@CBkAp@kAv@m@f@WRm@h@k@j@u@t@[^e@h@s@|@MRo@x@eB~BmCrDaBxBQVm@v@KLUZQVcF|GuHhKeBzBSXGHSXEFGFKPc@l@]f@SX[b@QV]d@m@t@GHY\\a@f@c@j@[\\Y\\k@j@u@r@KJo@h@u@n@[Tc@Xa@Vm@Z_Ab@g@Ti@Re@Ng@Pe@Jk@NUDg@Js@JSB[DQBc@Da@Dk@DU@q@@s@@[A{@ASA]C]Co@GgBQ}@Kg@GWCKAeAMA?a@EEA]Ec@Gs@Ku@KiAOQCsBW}BYqAOQCYEi@GsBWqBUkBSi@Gs@IYCmBSsAO]Ea@EeAMe@EYEcBSSCQCs@Mc@Ga@Ei@GeAM}@K_D_@gAMsC]mBUe@GsAQ}@MUESEm@Mm@OUGICUIOEUISG_@O]OQIKESKc@UIEc@W]SSMKG]UAAMIQOKIAAq@i@[Ya@_@o@m@OQCCaAeAm@o@a@c@[_@OQA?KKa@e@s@w@EEQQEEQSu@y@a@g@y@y@_BaBc@c@e@c@OOMKu@k@e@_@c@[YQe@Ya@Uy@c@ICWMq@Y_A]u@UOEo@OICi@K[GYEMCiAM_AIC?_AEeA?E?c@?_@?g@BY?I@k@Bu@HiANu@Lc@Lm@Lm@Pa@NQFUHc@Pe@Re@Rm@Xw@^i@Vc@TWLMFa@RgI~De@T_@RA?UJQJUJi@Xw@^iAj@uAp@aCjAYN{@`@uBdAgClAsAr@w@b@c@T_@TeAn@YRm@^a@XUNWPOLQJQLe@\\GDaAt@sAfA}@t@c@`@]ZKHiB`Ba@^]Z[\\KJQPe@d@GH[^Y\\C@u@`A[^[`@MNMPa@f@UX]f@w@hAm@|@C@_AzA}@vAU\\w@nAY`@QVu@jA_@h@]f@k@|@m@x@]h@GJe@r@[d@a@n@CBYd@m@~@]l@MR}@pACBU\\e@n@UV[^c@h@SVGFSVGHUVSX[b@a@j@GHINCD_@b@i@j@C@o@p@CBy@z@EBQREBQNIH_@^{@r@WRe@`@EBw@p@A@]T_@XA@a@ZYR_Ar@}@p@OJo@f@uA`Ao@d@u@j@A@OJMJq@f@m@b@URg@\\GFu@h@UPIFYRs@h@o@d@GFc@XsB|A[T_@XUPIFa@ZMLe@^WRk@h@GFYVYVCBu@r@]^QN_@h@ONQP[\\a@^QPg@h@WXg@h@UZY`@c@j@gA|AiAdBs@fACDy@xA_@l@INADOVEFCFc@v@MTi@dAUb@Wf@?@QZOXMXWf@a@l@U`@g@fAm@rA{@pBo@~AeAlC_@`AoBhFu@jBKVWl@[r@[x@[p@Qb@EJYl@Yn@Yl@?@Yj@[r@KPMVEHMV[r@qAdCqAbCsAbCmBbDa@r@A@W`@W^EHaAzAg@v@OT_@f@OVsAlBoBhCo@|@yAfBu@|@MNw@|@i@l@{A`BoBrBUTSTg@d@sDjDs@p@e@`@w@r@EBk@b@}DzCuH`G]VA?yFnEmCrB]XyDxCa@Z}AjAkAz@aBjAeDzBi@Z}@j@w@d@iCtAs@`@s@^cD~A{@`@oAh@}Ap@kAb@mBt@gFfBiC|@iC|@mL~Dq@VqDnAgBl@wLfEKBa@NA@gCz@eA\\a@NmBn@aBf@_@NeA\\mFlBmDpAiDlAgBn@a@Na@La@Ng@NeCt@a@Pa@LcBj@iBr@w@Z{@\\WHmDjA{@Xw@Vg@RMDi@T_@PWLc@Ti@Va@T]PaAl@o@`@MHc@Ze@\\SNm@d@[Xu@p@m@l@A@g@f@kAlAaBtBaAzAeAhBMVk@jAQ^[v@Wn@w@xB_@jA_@pASx@Mf@K`@CFWnAk@hDg@xD[tDEj@QpDQpCg@zIOxCa@`Ia@dII~AKlBEr@SzD@tAIp@ALIh@Mt@YbBMj@GVQv@Ol@A@Sv@Ux@[`A]tAk@pBELUr@Ob@Yl@Wh@QZEHQXWb@{@pAMPw@jAm@bAa@v@Q\\Qb@Wr@Ob@CHSt@Qt@GRIb@Kj@CPE`@CNI|@Ef@Ef@?JCj@?FCr@?BAz@?f@?N?b@@n@Bl@B|@?BFfAJlBHdADr@FjABZDp@NpCZnFXpF@DDxABz@@\\@~@BpBD~F@lBBbDBfF?~C@nC@tA?tBB|C@dELzY@bC?tA@lD@z@Af@A\\Ar@A`AGxA[nGAVc@nICh@IbBK`Bs@pNa@lH]lGIfBaAdRYfFk@|KQnDOrC[xFm@fLg@hJStDYbGIxAe@hJg@zJIjBU`EWbFUnEMpCKfBUpEGFCBAFCFCx@C`@MpDAh@AfACrB?nG"
                     },
                     "start_location" : {
                        "lat" : 46.1117073,
                        "lng" : -80.67029839999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.3 km",
                        "value" : 3291
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 237
                     },
                     "end_location" : {
                        "lat" : 46.451567,
                        "lng" : -81.00313750000001
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eGreater Sudbury Regional Road 46\u003c/b\u003e",
                     "polyline" : {
                        "points" : "aolzGnlemNAn@DxBBhH?|A@fAChD?PE|@GbBMnACNALQ~@?BE^Q`AQt@_@~AOl@Kb@CFEN]fA_B~EuBjGQj@GLSl@_AlC[z@gBfD{FlGg@ZsBnAaB|@_CjAmD`BmB`Ai@TsAbAeAz@}@`AiApAaArA_AvAg@~@gAvBmAdCcApBUb@_BvC{D`JqAlDQd@a@dAUl@ITe@tAQl@iAzEk@hDGf@ERM~AOlB_@|GKPA^_@rDATEVCVADCTIh@GZGZKd@e@|A"
                     },
                     "start_location" : {
                        "lat" : 46.4358488,
                        "lng" : -80.96983940000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.0 km",
                        "value" : 3960
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 318
                     },
                     "end_location" : {
                        "lat" : 46.4848059,
                        "lng" : -80.9893558
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eParis St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eGreater Sudbury Regional Road 80 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "iqozGr|kmNe@UWIWKYKe@S_@Q_@MgEyAc@OgA]cBk@cC}@kA[s@Mu@E{@BK?E?A?c@DYFa@Fm@H[DeALA?gABe@?i@Ce@CIAeAW]IKC[Ms@WoBo@SGMCUEi@EMASAgAK_AGSCg@G[Ec@K]Kc@OYMoBu@UGGAOEc@Gk@Wm@A_@?g@Aa@?E?M?UA]AA?WGQCMCYI[ImA[]Iy@Q_AUa@Wy@UeEiA_EeAqBi@OEWKm@MmBg@a@M}@SsA_@]Ci@[[UYSQQSYGG]g@o@aACCYc@]k@S_@Ye@e@s@e@q@g@g@YWc@]a@WICMEWGQCOAo@AqAEqCIUAgAMOCUISK[S_@]q@w@EEw@}@[]MSuAaBSUm@u@UYkAaBOQg@o@u@cAcB_C{@q@UIWCG?WAsAAgA?oBAaACi@UeAGyCD[?a@@I?k@?S?"
                     },
                     "start_location" : {
                        "lat" : 46.451567,
                        "lng" : -81.00313750000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 200
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 15
                     },
                     "end_location" : {
                        "lat" : 46.4866036,
                        "lng" : -80.9893285
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eBridge of Nations\u003c/b\u003e",
                     "polyline" : {
                        "points" : "aavzGnfimNWAE?]?m@?_A?G?gAA]?Q?U?e@A"
                     },
                     "start_location" : {
                        "lat" : 46.4848059,
                        "lng" : -80.9893558
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 753
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 106
                     },
                     "end_location" : {
                        "lat" : 46.4930982,
                        "lng" : -80.99047039999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eParis St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eGreater Sudbury Regional Road 80 N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "glvzGhfimN_BIYA}@KeAKqCYgAC{BCiDC{BDQDc@FgBz@gAh@cAbAeAfAi@f@"
                     },
                     "start_location" : {
                        "lat" : 46.4866036,
                        "lng" : -80.9893285
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 202
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 44
                     },
                     "end_location" : {
                        "lat" : 46.4931989,
                        "lng" : -80.9930198
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eElm St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eGreater Sudbury Regional Road 55\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{twzGlmimNQJ?p@?~@AtC?p@?~@?vB"
                     },
                     "start_location" : {
                        "lat" : 46.4930982,
                        "lng" : -80.99047039999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 163
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 64
                     },
                     "end_location" : {
                        "lat" : 46.4917321,
                        "lng" : -80.993008
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLisgar St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ouwzGj}imNV?lD?vAAF?"
                     },
                     "start_location" : {
                        "lat" : 46.4931989,
                        "lng" : -80.9930198
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "ytvmG~yy|MbmAcHb~@q]vu@nHb\\~u@zo@cW|cB}l@vr@~^ljAfvAv{@r~Fxn@xt@py@xa@tdDrcFjjBfvHzqBdoBzuBr|AjjDb~Et{CtiGzhA|cBviDt{E~gB~dBtl@bG`b@sT|bBqd@noCi_@trA?lu@th@~bAkU|jAe@~~EagAhdBhcBz|@fsBnOl~EfdAtgEhiAdiN_@dsBwt@peBmDlzB|_@`oCt}@vtFl]~aF|UtsHfcA~{GjlAl`GbgCrnG~sBdxDlGdeBgI|~Bba@xaF~}@fjDbq@hsFlk@dwF~I`|E`OvaD`p@z~BxmBd~CfpA`|F|p@`lGwc@x{@a|F~z@ihKjrAgcBzHehQniCsbSrnDccEp_DqpE`s@}|C~e@o~Gtd@_qD~lAeqDlv@qdKfgBcoG|RazAhMe`BfhBoj@|i@{q@uMocD{sCg~@owDql@yb@}X~]atAdoA}oEpwD}cCj|Bg_Fl{D}fAvK}rAkjAszAoqD{zBmwDmnC_hBofEuuAw{Bib@woDpb@}iA`dBilDbaCg{@hhBamBap@c~@}Tad@`\\}`BjzAqf@~nCgYl[{oAH}nC{HsbDnaAatAtLwrC`jCobDbQyoDzTufAse@qc@`_@m}Bde@waDsi@kc@s^saAbK{oBjrA_sBeKq|Iho@quAaMgmAlGeuCh{AcaEhmAwu@vIsr@jt@itA`EuoAt{@uqBjOwiAbnB{bAbvAw^|fCkKhnDuNzrAif@f]ux@biAwxAxgCor@nrDaqCv}B_nApqBcxAjbB_dBjj@kzAnbBiZpcBeC`iBgfAdyCk}C`{DifLjvQ{cDlyIik@fxBwvA`qCihBz~Ai~Ad`@cnC~sA_mBj{AucDbqEubEdsBgkFftCevBpp@ai@le@c\\zqBmmBfaBodD||AmtGvgBgbBmWc~B~v@khBzd@_oAjPmx@wFmfDog@eeAkW_kC|VubDlrCovFj~GgjBlyA{jAbZiL}}B`GqjF`j@ee@bzAkBhw@lAjKhl@pVhg@djAuBrwA{uAh`@u]j_@x`@fEeS`MeScUvi@e^wc@uMdK_\\he@iwA`eAypAiTySg_AqfBk@sbAlOaRpfAkI|nFnIv~@cSdj@aoE`bD{`AvlAyiDh}@}iBt~DmmAnyB_eApQ{mA|b@kgBxcDw`Azl@imDiiAugBvyAi}A{CwgAig@_mAlCanAxeAknBxvBibBvcCu_E~eBwd@bn@gR~kBiKf{B{WjzIws@fkA}i@d_BymA{KoqAid@_n@{Zku@zIbH|J"
         },
         "summary" : "ON-115 S and ON-400 N",
         "warnings" : [],
         "waypoint_order" : [ 0, 1 ]
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
