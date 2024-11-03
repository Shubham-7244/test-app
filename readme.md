##VM arguments:
-Dmule.vaultKey=unicorn -Denv=dev -Danypoint.platform.gatekeeper=disabled


##Deploy arguments
mvn clean deploy -DmuleDeploy -Denv=dev -Dmule.vaultKey=Unicorn -Dregion=eu-west-1 -Dworkers=1 -DworkerType=MICRO -Danypoint.platform.gatekeeper=disabled -DskipMuitTests -Pcloudhub-dev
