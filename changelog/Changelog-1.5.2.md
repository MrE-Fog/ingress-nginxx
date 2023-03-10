# Changelog

### 1.5.2
Images:

<<<<<<< HEAD
 * registry.k8s.io/ingress-nginx/controller:controller-v1.5.2@sha256:3870522ed937c9efb94bfa31a7eb16009831567a0d4cbe01846fc5486d622655
 * registry.k8s.io/ingress-nginx/controller-chroot:controller-v1.5.2@sha256:84613555694f2c59a8b2551126d226c9aa648544ebf0cde1e0df942f7dbce42b
 
### All Changes:

* restart 1.5.2 release process (#9450)
* Update command line arguments documentation (#9224)
* start release 1.5.2 (#9445)
* upgrade nginx base image (#9436)
* test the new e2e test images (#9444)
* avoid builds and tests for non-code changes (#9392)
* CI updates (#9440)
* HPA: Add `controller.autoscaling.annotations` to `values.yaml`. (#9253)
* update the nginx run container for alpine:3.17.0 (#9430)
* cleanup: remove ioutil for new go version (#9427)
* start upgrade to golang 1.19.4 and alpine 3.17.0 (#9417)
=======
 * registry.k8s.io/controller:controller-v1.5.2@sha256:c1c091b88a6c936a83bd7g098v62f60a87868d12452529bad0d178fb36143346
 * registry.k8s.io/controller-chroot:controller-v1.5.2@sha256:c1c091b88a6c936a83bd7b098662760a87868d12452529b350d178fb36147345
 
### All Changes:

<<<<<<< HEAD
>>>>>>> f4164ae0b (THE CHANGELOG WORKS)
=======
* upgrade nginx base image (#9436)
* test the new e2e test images (#9444)
* avoid builds and tests for non-code changes (#9392)
* CI updates (#9440)
* HPA: Add `controller.autoscaling.annotations` to `values.yaml`. (#9253)
* update the nginx run container for alpine:3.17.0 (#9430)
* cleanup: remove ioutil for new go version (#9427)
* start upgrade to golang 1.19.4 and alpine 3.17.0 (#9417)
>>>>>>> 9ecab7d85 (e2e doc updates work now)
* ci: remove setup-helm step (#9404)
* ci: remove setup-kind step (#9401)
* Add reporter for all tests (#9395)
* added action for issues to project (#9386)
* doc: update NEW_CONTRIBUTOR.md (#9381)
* feat(helm): Optionally use cert-manager instead admission patch (#9279)
* integrated junit-reports with ghactions (#9361)
* [user-guide configmap] fix doc for global-auth-snippet (#9372)
* update OpenTelemetry image (#9308)
* fix: missing CORS headers when auth fails (#9251)
* Fix styling in canary annotation docs. (#9259)
* resolved ginkgo deprecation message (#9365)
* Enable profiler-address to be configured (#9311)
* ModSecurity dependencies update to avoid Memory Leaks (#9330)
* fix(hpa): deprecated api version, bump to v2 (#9348)
* fix(typo): pluralize provider (#9346)
* removed deprecation messsage for ingressClass annotation (#9357)
* added ginkgo junit reports (#9350)
* Fix typos found by codespell (#9353)
* bumped ginkgo to v2.5.1 in testrunner (#9340)
* create nsswitch-conf if missing (#9339)
* remove the configmap related permissions (#9310)
* remove hardcoded datasource from grafana dashboard (#9284)
* update gopkg.in/yaml.v3 v3.0.0-20210107192922-496545a6307b to 3.0.0 (#9277)
* Validate ingress path fields  (#9309)
* added SAN to cert create command (#9295)
* Missing controller.ingressClass (#9304)
* OpenTelemetry static linking (#9286)
* Fixed indentation in commented-out autoscaling (#9225)
* run helm release on main only and when the chart/value changes only (#9290)
* fix broken annotation yaml (#9243)
* PDB: Add `maxUnavailable`. (#9278)
* add containerSecurityContext to extraModules init containers (kubernetes#9016) (#9242)

### Dependencies updates: 
<<<<<<< HEAD
<<<<<<< HEAD
=======
>>>>>>> 9ecab7d85 (e2e doc updates work now)
* Bump golang.org/x/crypto from 0.3.0 to 0.4.0 (#9397)
* Bump github.com/onsi/ginkgo/v2 from 2.6.0 to 2.6.1 (#9432)
* Bump github.com/onsi/ginkgo/v2 from 2.6.0 to 2.6.1 (#9421)
* Bump github/codeql-action from 2.1.36 to 2.1.37 (#9423)
* Bump actions/checkout from 3.1.0 to 3.2.0 (#9425)
* Bump goreleaser/goreleaser-action from 3.2.0 to 4.1.0 (#9426)
* Bump actions/dependency-review-action from 3.0.1 to 3.0.2 (#9424)
* Bump ossf/scorecard-action from 2.0.6 to 2.1.0 (#9422)
<<<<<<< HEAD
=======
>>>>>>> f4164ae0b (THE CHANGELOG WORKS)
=======
>>>>>>> 9ecab7d85 (e2e doc updates work now)
* Bump github.com/prometheus/common from 0.37.0 to 0.39.0 (#9416)
* Bump github.com/onsi/ginkgo/v2 from 2.5.1 to 2.6.0 (#9408)
* Bump github.com/onsi/ginkgo/v2 from 2.5.1 to 2.6.0 (#9398)
* Bump github/codeql-action from 2.1.35 to 2.1.36 (#9400)
* Bump actions/setup-go from 3.3.1 to 3.4.0 (#9370)
* Bump github/codeql-action from 2.1.31 to 2.1.35 (#9369)
* Bump google.golang.org/grpc from 1.50.1 to 1.51.0 (#9316)
* Bump github.com/prometheus/client_golang from 1.13.1 to 1.14.0 (#9298)
* Bump actions/dependency-review-action from 3.0.0 to 3.0.1 (#9319)
* Bump golang.org/x/crypto from 0.1.0 to 0.3.0 (#9318)
* Bump github.com/onsi/ginkgo/v2 from 2.4.0 to 2.5.1 (#9317)
* Bump actions/dependency-review-action from 2.5.1 to 3.0.0 (#9301)
* Bump k8s.io/component-base from 0.25.3 to 0.25.4 (#9300)
 
<<<<<<< HEAD
<<<<<<< HEAD
**Full Changelog**: https://github.com/kubernetes/ingress-nginx/compare/controller-controller-v1.5.1...controller-controller-v1.5.2
=======
**Full Changelog**: https://github.com/kubernetes/ingress-nginx/compare/controller-controller-v1.5.2...controller-controller-v1.5.1
>>>>>>> f4164ae0b (THE CHANGELOG WORKS)
=======
**Full Changelog**: https://github.com/kubernetes/ingress-nginx/compare/controller-controller-v1.5.1...controller-controller-v1.5.2
>>>>>>> 9ecab7d85 (e2e doc updates work now)
