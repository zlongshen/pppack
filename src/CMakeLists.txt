add_library(pppack SHARED
  banfac.f
  banslv.f
  bchfac.f
  bchslv.f
  bsplpp.f
  bsplvb.f
  bsplvd.f
  bspp2d.f
  bvalue.f
  chol1d.f
  colloc.f
  colpnt.f
  cubspl.f
  cwidth.f
  difequ.f
  eqblok.f
  interv.f
  knots.f
  newnot.f
  ppvalu.f
  putit.f
  setupq.f
  slvblktext.f
  smooth.f
  spli2d.f
  splint.f
  splopt.f
  tautsp.f)

install(TARGETS pppack
  RUNTIME DESTINATION bin
  LIBRARY DESTINATION lib)
