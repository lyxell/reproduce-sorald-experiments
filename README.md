## Rule 2095

* Original claim: 160/161 (99%) projects compile successfully and has no
  failing tests

### Replication

Out of the 161 projects only 48 had violations that led Sorald to perform a repair.

* Number of projects with changed files: 48
* Number of projects with compile errors: 32/48
* Number of projects with other errors: 2/48
* Number of projects with test failures: 1/48
* Number of projects that compile successfully and has no failing tests: 14/48 (29%)

Project                               | Author              | Result    
--------------------------------------|---------------------|--------------
100-words-design-patterns-java        | dstar55             | No violations repaired
BPlusTree                             | andylamp            | [OK](./data/BPlusTree/2095/compile.log), [Diff](./data/BPlusTree/2095/repair.diff)
ChangeSkin                            | games647            | No violations repaired
ExecDashboard                         | Hygieia             | No violations repaired
GoogleAuth                            | wstrange            | No violations repaired<sup>[1](#user-content-f1)</sup>
HAP-Java                              | hap-java            | No violations repaired
HTTP-Proxy-Servlet                    | mitre               | [Compile errors](./data/HTTP-Proxy-Servlet/2095/compile.log), [Diff](./data/HTTP-Proxy-Servlet/2095/repair.diff)
JWT4B                                 | ozzi-               | No violations repaired
MobArena                              | garbagemule         | No violations repaired<sup>[1](#user-content-f1)</sup>
MsgViewer                             | lolo101             | [Compile errors](./data/MsgViewer/2095/compile.log), [Diff](./data/MsgViewer/2095/repair.diff)
MutabilityDetector                    | MutabilityDetector  | No violations repaired
MyPerf4J                              | LinShunKang         | [OK](./data/MyPerf4J/2095/compile.log), [Diff](./data/MyPerf4J/2095/repair.diff)
Nukkit                                | CloudburstMC        | [Compile errors](./data/Nukkit/2095/compile.log), [Diff](./data/Nukkit/2095/repair.diff)
OpenTripPlanner                       | opentripplanner     | [Compile errors](./data/OpenTripPlanner/2095/compile.log), [Diff](./data/OpenTripPlanner/2095/repair.diff)
Paguro                                | GlenKPeterson       | [OK](./data/Paguro/2095/compile.log), [Diff](./data/Paguro/2095/repair.diff)
Prism-Bukkit                          | AddstarMC           | [Compile errors](./data/Prism-Bukkit/2095/compile.log), [Diff](./data/Prism-Bukkit/2095/repair.diff)
RestFixture                           | smartrics           | [OK](./data/RestFixture/2095/compile.log), [Diff](./data/RestFixture/2095/repair.diff)
Scientist4J                           | rawls238            | No violations repaired
Simple-DSL                            | LMAX-Exchange       | No violations repaired
Sudachi                               | WorksApplications   | No violations repaired
T-SNE-Java                            | lejon               | No violations repaired
TinyRadius                            | ctran               | No violations repaired
Vitro                                 | vivo-project        | [Compile errors](./data/Vitro/2095/compile.log), [Diff](./data/Vitro/2095/repair.diff)
Wikidata-Toolkit                      | Wikidata            | [Compile errors](./data/Wikidata-Toolkit/2095/compile.log), [Diff](./data/Wikidata-Toolkit/2095/repair.diff)
YCSB                                  | brianfrankcooper    | [Other errors](./data/YCSB/2095/compile.log), [Diff](./data/YCSB/2095/repair.diff)
Yank                                  | knowm               | No violations repaired
aXMLRPC                               | gturri              | No violations repaired
aesh                                  | aeshell             | [Other errors](./data/aesh/2095/compile.log), [Diff](./data/aesh/2095/repair.diff)
aho-corasick                          | robert-bor          | No violations repaired
amidst                                | toolbox4minecraft   | No violations repaired
annoy-java                            | spotify             | [OK](./data/annoy-java/2095/compile.log), [Diff](./data/annoy-java/2095/repair.diff)
apk-parser                            | hsiafan             | No violations repaired<sup>[3](#user-content-f3)</sup>
argparse4j                            | argparse4j          | No violations repaired
arthas                                | alibaba             | [Compile errors](./data/arthas/2095/compile.log), [Diff](./data/arthas/2095/repair.diff)
bitfinex-v2-wss-api-java              | jnidzwetzki         | No violations repaired
browscap-java                         | blueconic           | No violations repaired
build-helper-maven-plugin             | mojohaus            | No violations repaired<sup>[2](#user-content-f2)</sup>
byteunits                             | JakeWharton         | No violations repaired
carml                                 | carml               | No violations repaired
cbor-java                             | c-rack              | No violations repaired
commafeed                             | Athou               | No violations repaired
dataenum                              | spotify             | No violations repaired
dd-plist                              | 3breadt             | [OK](./data/dd-plist/2095/compile.log), [Diff](./data/dd-plist/2095/repair.diff)
docker-java-api                       | amihaiemil          | No violations repaired
elasticsearch-maven-plugin            | alexcojocaru        | No violations repaired<sup>[2](#user-content-f2)</sup>
embedmongo-maven-plugin               | joelittlejohn       | [Compile errors](./data/embedmongo-maven-plugin/2095/compile.log), [Diff](./data/embedmongo-maven-plugin/2095/repair.diff)
epubcheck                             | w3c                 | [Compile errors](./data/epubcheck/2095/compile.log), [Diff](./data/epubcheck/2095/repair.diff)
ethernet-ip                           | digitalpetri        | No violations repaired
example-java                          | codecov             | No violations repaired
externalsortinginjava                 | lemire              | [Compile errors](./data/externalsortinginjava/2095/compile.log), [Diff](./data/externalsortinginjava/2095/repair.diff)
failsafe                              | jhalterman          | No violations repaired
fast-object-pool                      | DanielYWoo          | No violations repaired
fast-uuid                             | jchambers           | No violations repaired
flip-tables                           | JakeWharton         | No violations repaired
galimatias                            | smola               | No violations repaired
geohash-java                          | kungfoo             | No violations repaired
geometry-api-java                     | Esri                | [Compile errors](./data/geometry-api-java/2095/compile.log), [Diff](./data/geometry-api-java/2095/repair.diff)
gerrit-rest-java-client               | uwolfer             | No violations repaired
gocd-build-github-pull-requests       | ashwanthkumar       | No violations repaired
gocd-slack-build-notifier             | ashwanthkumar       | No violations repaired
goodsKill                             | techa03             | [Compile errors](./data/goodsKill/2095/compile.log), [Diff](./data/goodsKill/2095/repair.diff)
google-java-format                    | google              | No violations repaired
gson-fire                             | julman99            | No violations repaired
guava-beta-checker                    | google              | No violations repaired
hamcrest-date                         | eXparity            | No violations repaired
hilbert-curve                         | davidmoten          | No violations repaired
jMetal                                | jMetal              | [Compile errors](./data/jMetal/2095/compile.log), [Diff](./data/jMetal/2095/repair.diff)
java-ascii-render                     | indvd00m            | No violations repaired
java-cookie                           | js-cookie           | No violations repaired
java-faker                            | DiUS                | No violations repaired
java-jdbc                             | opentracing-contrib | No violations repaired
java-kafka-client                     | opentracing-contrib | No violations repaired
jbehave-junit-runner                  | valfirst            | No violations repaired
jd-cli                                | kwart               | No violations repaired
jmeter-elasticsearch-backend-listener | delirius325         | No violations repaired
jna-gmp                               | square              | No violations repaired
jolokia                               | rhuss               | [Compile errors](./data/jolokia/2095/compile.log), [Diff](./data/jolokia/2095/repair.diff)
joshua                                | apache              | [Compile errors](./data/joshua/2095/compile.log), [Diff](./data/joshua/2095/repair.diff)
jpass                                 | gaborbata           | [OK](./data/jpass/2095/compile.log), [Diff](./data/jpass/2095/repair.diff)
jsch-nio                              | lucastheisen        | No violations repaired
json-schema-validator                 | networknt           | No violations repaired
jtar                                  | kamranzafar         | [Compile errors](./data/jtar/2095/compile.log), [Diff](./data/jtar/2095/repair.diff)
jts                                   | locationtech        | [Compile errors](./data/jts/2095/compile.log), [Diff](./data/jts/2095/repair.diff)
junit4                                | junit-team          | [Compile errors](./data/junit4/2095/compile.log), [Diff](./data/junit4/2095/repair.diff)
juniversalchardet                     | albfernandez        | No violations repaired
jvm-profiler                          | uber-common         | No violations repaired
kafka-topology-builder                | kafka-ops           | [OK](./data/kafka-topology-builder/2095/compile.log), [Diff](./data/kafka-topology-builder/2095/repair.diff)
kcp-netty                             | szhnet              | No violations repaired
lambda                                | palatable           | No violations repaired
license-maven-plugin                  | mycila              | [OK](./data/license-maven-plugin/2095/compile.log), [Diff](./data/license-maven-plugin/2095/repair.diff)
lorsource                             | maxcom              | [OK](./data/lorsource/2095/compile.log), [Diff](./data/lorsource/2095/repair.diff)
matomo-java-tracker                   | matomo-org          | No violations repaired
maven-cucumber-reporting              | damianszczepanik    | No violations repaired
mirus                                 | salesforce          | No violations repaired
miso-lims                             | miso-lims           | [Compile errors](./data/miso-lims/2095/compile.log), [Diff](./data/miso-lims/2095/repair.diff)
missinglink                           | spotify             | No violations repaired
model-citizen                         | mguymon             | No violations repaired
modelmapper                           | modelmapper         | [Compile errors](./data/modelmapper/2095/compile.log), [Diff](./data/modelmapper/2095/repair.diff)
movsim                                | movsim              | [OK](./data/movsim/2095/compile.log), [Diff](./data/movsim/2095/repair.diff)
mtg-sdk-java                          | MagicTheGathering   | No violations repaired
nacos-spring-project                  | nacos-group         | No violations repaired
nanojson                              | mmastrac            | No violations repaired
nbvcxz                                | GoSimpleLLC         | No violations repaired
nfe                                   | wmixvideo           | No violations repaired
nlp-lang                              | NLPchina            | [Compile errors](./data/nlp-lang/2095/compile.log), [Diff](./data/nlp-lang/2095/repair.diff)
obfuscator                            | superblaubeere27    | [Compile errors](./data/obfuscator/2095/compile.log), [Diff](./data/obfuscator/2095/repair.diff)
openhtmltopdf                         | danfickle           | [OK](./data/openhtmltopdf/2095/compile.log), [Diff](./data/openhtmltopdf/2095/repair.diff)
openmessaging-java                    | openmessaging       | No violations repaired
openstack4j                           | ContainX            | [Compile errors](./data/openstack4j/2095/compile.log), [Diff](./data/openstack4j/2095/repair.diff)
owasp-security-logging                | javabeanz           | No violations repaired
password4j                            | Password4j          | No violations repaired
pitest                                | hcoles              | No violations repaired<sup>[2](#user-content-f2)</sup>
pkts                                  | aboutsip            | No violations repaired
proguard-maven-plugin                 | wvengen             | No violations repaired
prometheus-hystrix                    | ahus1               | No violations repaired
protostuff                            | protostuff          | [Compile errors](./data/protostuff/2095/compile.log), [Diff](./data/protostuff/2095/repair.diff)
reader                                | sismics             | No violations repaired
redpen                                | redpen-cc           | [OK](./data/redpen/2095/compile.log), [Diff](./data/redpen/2095/repair.diff)
rescu                                 | mmazi               | No violations repaired
rest-driver                           | rest-driver         | No violations repaired
resteasy-examples                     | resteasy            | No violations repaired
retrofit-spring-boot-starter          | LianjiaTech         | No violations repaired
robot                                 | ontodev             | [Compile errors](./data/robot/2095/compile.log), [Diff](./data/robot/2095/repair.diff)
rxjava-jdbc                           | davidmoten          | No violations repaired
rxjava2-extras                        | davidmoten          | [Compile errors](./data/rxjava2-extras/2095/compile.log), [Diff](./data/rxjava2-extras/2095/repair.diff)
salvation                             | shapesecurity       | No violations repaired
sardine                               | lookfirst           | No violations repaired<sup>[2](#user-content-f2)</sup>
sds                                   | didi                | No violations repaired
semantic-metrics                      | spotify             | No violations repaired
semver4j                              | vdurmont            | No violations repaired
sensitive                             | houbb               | No violations repaired
simple-excel                          | tobyweston          | No violations repaired
simplenlg                             | simplenlg           | [Compile errors](./data/simplenlg/2095/compile.log), [Diff](./data/simplenlg/2095/repair.diff)
singer                                | pinterest           | [Compile errors](./data/singer/2095/compile.log), [Diff](./data/singer/2095/repair.diff)
sisyphus                              | houbb               | No violations repaired
slack-java-webhook                    | ashwanthkumar       | No violations repaired
solr-redis                            | sematext            | No violations repaired
sparkey-java                          | spotify             | [Test failures](./data/sparkey-java/2095/compile.log), [Diff](./data/sparkey-java/2095/repair.diff)
spatial-framework-for-hadoop          | Esri                | No violations repaired
specification-arg-resolver            | tkaczmarzyk         | No violations repaired
spring-context-support                | alibaba             | No violations repaired
spring-guice                          | spring-projects     | No violations repaired
sql-builder                           | jonathanhds         | No violations repaired
sql-to-mongo-db-query-converter       | vincentrussell      | [Compile errors](./data/sql-to-mongo-db-query-converter/2095/compile.log), [Diff](./data/sql-to-mongo-db-query-converter/2095/repair.diff)
sqlite-jdbc                           | xerial              | [OK](./data/sqlite-jdbc/2095/compile.log), [Diff](./data/sqlite-jdbc/2095/repair.diff)
stream-registry                       | ExpediaGroup        | No violations repaired
suffixtree                            | abahgat             | No violations repaired
swagger-dubbo                         | Sayi                | No violations repaired
tetrad                                | cmu-phil            | [Compile errors](./data/tetrad/2095/compile.log), [Diff](./data/tetrad/2095/repair.diff)
torpedoquery                          | xjodoin             | No violations repaired
utah-parser                           | sonalake            | No violations repaired
vertx-completable-future              | cescoffier          | No violations repaired
vertx-jdbc-client                     | vert-x3             | No violations repaired
vertx-kafka-client                    | vert-x3             | No violations repaired
vue-gwt                               | VueGWT              | No violations repaired
web3j-maven-plugin                    | web3j               | No violations repaired
webapp-runner                         | heroku              | No violations repaired<sup>[2](#user-content-f2)</sup>
weblogic-monitoring-exporter          | oracle              | No violations repaired<sup>[2](#user-content-f2)</sup>
zendesk-java-client                   | cloudbees-oss       | No violations repaired
zip4j                                 | srikanth-lingala    | [Compile errors](./data/zip4j/2095/compile.log), [Diff](./data/zip4j/2095/repair.diff)
zt-process-killer                     | zeroturnaround      | No violations repaired<sup>[1](#user-content-f1)</sup>

<span id="f1">1:</span> One violation in a file that does not
belong to and is not compiled nor tested by the project

<span id="f2">2:</span> Sorald claims to repair files but in
reality the files are unchanged

<span id="f3">3:</span> Sorald claims to repair files but in
reality only imports are added 
