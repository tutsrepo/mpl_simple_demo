@Library('mpl@release') _

node( '' ) {
  stage( 'Application Checkout' ) {
    MPLModule('Checkout')
  }
  stage( 'Build' ) {
    MPLModule()
  }
  stage( 'Custom Stage' ) {
    echo 'Any custom steps you want'
  }
  stage( 'Test' ) {
    MPLModule()
  }
}
