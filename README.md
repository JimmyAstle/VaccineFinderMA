[![mass-region-vaccine-check](https://github.com/JimmyAstle/VaccineFinderMA/actions/workflows/sites-check.yml/badge.svg)](https://github.com/JimmyAstle/VaccineFinderMA/actions/workflows/sites-check.yml)
# Massachusetts Region Covid 19 Vaccine Checker

**This repo is now no longer checking for vaccine appointments**

This repository checks several CVS locations in the Massachusetts Region for availability of Covid 19 vaccination appointments.

Follow <img alt="" src="https://favicons.githubusercontent.com/www.twitter.com" height="13"> **[Twitter bot](https://twitter.com/FinderMass)** <img alt="" src="https://favicons.githubusercontent.com/www.twitter.com" height="13"> to get notified of new appointment availability!

<!--start: status pages-->
**Last Updated**: 2021-05-26 10:10 AM

| Site                | Status         |
| ------------------- | -------------- |
| <img alt="" src="https://favicons.githubusercontent.com/www.cvs.com" height="13"> [CVS](https://www.cvs.com/immunizations/covid-19-vaccine)               | :white_check_mark: Available ACTON AGAWAM ALLSTON AMHERST ARLINGTON ATHOL BELMONT BEVERLY BOSTON BRAINTREE BRIGHTON BROCKTON BURLINGTON CAMBRIDGE CANTON CARVER CHELSEA CHICOPEE DANVERS DEDHAM DORCHESTER DRACUT EAST BOSTON EAST FALMOUTH FALL RIVER FALMOUTH FITCHBURG FRAMINGHAM GREENFIELD HANOVER HARWICH HARWICHPORT HAVERHILL HOLBROOK HOLYOKE HOPKINTON HUDSON HYANNIS HYDE PARK IPSWICH LAWRENCE LEOMINSTER LONGMEADOW LOWELL LUNENBURG LYNN MALDEN MARBLEHEAD MATTAPAN MAYNARD MEDFIELD MEDFORD METHUEN MIDDLEBOROUGH MIDDLETON MILFORD NATICK NEW BEDFORD NEWBURYPORT NEWTON NORTH ANDOVER NORTH BILLERICA NORTH EASTON NORTH GRAFTON OXFORD PALMER PEABODY PLYMOUTH PROVINCETOWN QUINCY RANDOLPH REVERE ROSLINDALE SALEM SALISBURY SANDWICH SEEKONK SOUTH HAMILTON SOUTH YARMOUTH SOUTHBRIDGE SPRINGFIELD STONEHAM STOUGHTON STURBRIDGE TAUNTON WALTHAM WAREHAM WATERTOWN WAYLAND WEBSTER WELLESLEY WEST BRIDGEWATER WEST NEWTON WEST SPRINGFIELD WESTBOROUGH WESTFIELD WESTPORT WEYMOUTH WILBRAHAM WILMINGTON WINCHENDON WINTHROP WOBURN WOLLASTON WORCESTER       |
<!--end: status pages-->

## Site Information

This checks the following locations approximatly every 15 minutes using GitHub Actions.

* The following CVS locations:
  *  abington
  *  acton
  *  agawam
  *  allston
  *  amherst
  *  arlington
  *  ashland
  *  athol
  *  attleboro
  *  bedford
  *  belchertown
  *  bellingham
  *  belmont
  *  beverly
  *  billerica
  *  boston
  *  bourne
  *  braintree
  *  brighton
  *  brockton
  *  brookline
  *  burlington
  *  cambridge
  *  canton
  *  carver
  *  chatham
  *  chelsea
  *  chestnut hill
  *  chicopee
  *  cohasset
  *  concord
  *  danvers
  *  dedham
  *  dorchester
  *  dracut
  *  east boston
  *  east bridgewater
  *  east falmouth
  *  everett
  *  fall river
  *  falmouth
  *  fitchburg
  *  foxborough
  *  framingham
  *  georgetown
  *  gloucester
  *  granby
  *  great barrington
  *  greenfield
  *  hadley
  *  hanover
  *  hanson
  *  harwich
  *  harwichport
  *  haverhill
  *  hingham
  *  holbrook
  *  holliston
  *  holyoke
  *  hopkinton
  *  hudson
  *  hyannis
  *  hyde park
  *  ipswich
  *  kingston
  *  lanesborough
  *  lawrence
  *  leominster
  *  lexington
  *  longmeadow
  *  lowell
  *  lunenburg
  *  lynn
  *  malden
  *  marblehead
  *  marlborough
  *  mashpee
  *  mattapan
  *  maynard
  *  medfield
  *  medford
  *  methuen
  *  middleborough
  *  middleton
  *  milford
  *  millbury
  *  millis
  *  natick
  *  needham
  *  new bedford
  *  newburyport
  *  newton
  *  north andover
  *  north attleborough
  *  north billerica
  *  north dartmouth
  *  north easton
  *  north grafton
  *  northampton
  *  norwell
  *  orleans
  *  oxford
  *  palmer
  *  peabody
  *  plainville
  *  plymouth
  *  provincetown
  *  quincy
  *  randolph
  *  reading
  *  revere
  *  roslindale
  *  rowley
  *  salem
  *  salisbury
  *  sandwich
  *  saugus
  *  seekonk
  *  sharon
  *  somerville
  *  south easton
  *  south hamilton
  *  south weymouth
  *  south yarmouth
  *  southbridge
  *  southwick
  *  springfield
  *  stoneham
  *  stoughton
  *  sturbridge
  *  swansea
  *  taunton
  *  waltham
  *  wareham
  *  watertown
  *  wayland
  *  webster
  *  wellesley
  *  west bridgewater
  *  west newton
  *  west springfield
  *  westborough
  *  westfield
  *  westford
  *  westport
  *  westwood
  *  weymouth
  *  wilbraham
  *  wilmington
  *  winchendon
  *  winchester
  *  winthrop
  *  woburn
  *  wollaston
  *  worcester
  *  wrentham



## Historical data

Historical availability data from previous checks can be found in the [data/site-data.csv](data/site-data.csv) spreadsheet.

## Acknowledgements

The code in this repo is a modified version of the code found here [CapitalRegionVaccine](https://github.com/CapitalRegionVaccine/CapitalRegionVaccine)

## 📄 License

- Code: [MIT](./LICENSE)
