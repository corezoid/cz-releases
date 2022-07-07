# Changelog

## gitcall

### 2.4.2 - 2022-07-07

GIT-462: declare task queue on runservice call

Closes GIT-462

See merge request gitcall/gitcall!311

#### Merged

- GIT-462: declare task queue on runservice call `#311`
- log reply status and message `#310`

#### Fixed

- Merge branch 'GIT-462-declare-task-queue-on-runservice' into '2.4-dev' `#GIT-462` `#GIT-462` `#GIT-462`
- GIT-462: declare task queue on runservice call `#GIT-462`

### 2.4.1 - 2022-06-17

GIT-460: Update dundergitcall sdk to v2

Closes GIT-460

See merge request gitcall/gitcall!309

#### Merged

- GIT-460: Update dundergitcall sdk to v2 `#309`
- GIT-460: Do not upgrade dundergitcall image when running existing deployment `#308`
- GIT-459: migrations new approach `#307`
- GIT-448: Usercode autoscale `#306`
- GIT-447: java fix args (Part 2) `#305`
- GIT-447: java args fix `#303`
- GIT-438: add concurency, timeout options to policy. `#302`
- DBCAL-171: snyk monitor `#301`
- GIT-433: Snyk scanner `#300`

#### Fixed

- Merge branch 'GIT-460-usercode-protocl-version' into '2.4-dev' `#GIT-460` `#GIT-460` `#GIT-460`
- Merge branch 'GIT-460-usercode-protocl-version' into '2.4-dev' `#GIT-460` `#GIT-460` `#GIT-460`
- Merge remote-tracking branch 'origin/2.4-dev' into GIT-460-usercode-protocl-version `#GIT-460`
- Merge branch 'GIT-459-migrations-new-approach' into '2.4-dev' `#GIT-459` `#GIT-459` `#GIT-459`
- GIT-460: do not update dundergitcall image if starting same deploy, not new `#GIT-460`
- GIT-459: migrations new approach `#GIT-459`
- Merge branch 'GIT-448-usercode-autoscale' into '2.4-dev' `#GIT-448` `#GIT-448` `#GIT-448`
- GIT-448: usercode autoscale `#GIT-448`
- Merge branch 'GIT-447-java-args-fix2' into '2.4-dev' `#GIT-447` `#GIT-447` `#GIT-447`
- Merge branch 'GIT-447-java-args-fix' into '2.4-dev' `#GIT-447` `#GIT-447` `#GIT-447`
- GIT-447: java args fix `#GIT-447`
- Merge branch 'GIT-438-configure-concurency' into '2.3-dev' `#GIT-438` `#GIT-438` `#GIT-438`
- GIT-438: add task size option `#GIT-438`
- Merge branch 'DBCAL-171-sync-monitor' into '2.3-dev' `#DBCAL-171` `#DBCAL-171` `#DBCAL-171`
- GIT-438: add concurency, timeout options to policy. `#GIT-438`
- Merge branch 'GIT-433-snyk-scanner' into '2.3-dev' `#GIT-433` `#GIT-433` `#GIT-433`
- GIT-433: snyk scanner `#GIT-433`
- GIT-433: snyk scanner `#GIT-433`

## gitcall_amulet

### 1.2.0 - 2022-06-15

#### Merged

- GIT-452: fix tests: gitcall 2.4 `#11`
- COR-8767: add kube-score linter `#10`
- COR-8717: validate kube resources `#9`

#### Fixed

- Merge branch 'GIT-452-fix-tests-after-dundergitcall-usercode-proxy-rewrite' into '1.2-dev' `#GIT-452` `#GIT-452`
- Merge branch 'COR-8767-add-kubescore-linter' into '1.1-dev' `#COR-8767` `#COR-8767`
- Merge branch 'COR-8717-valide-kube-recources' into '1.1-dev' `#COR-8717` `#COR-8717`
- Merge branch '1.1-dev' into 'COR-8717-valide-kube-recources' `#COR-8717`

## gitcall_docker_server

No changes

## gitcall_network_policy

No changes

## gitcall_pimp

### 1.1.3 - 2022-06-06

GIT-432: AutomountServiceAccountToken = false

Closes GIT-432

See merge request gitcall/services-pimp!89

#### Merged

- GIT-432: AutomountServiceAccountToken = false `#89`
- DBCAL-151: Describe support several pods `#88`
- COR-8767: add kube-score linter `#87`
- COR-8691: clusterRole is deprecated `#86`
- COR-8717: validate kube resources -- moved kubeconform job to test stage `#85`
- COR-8717: validate kube resources `#84`
- COR-8248: "Generate changelog" `#79`
- COR-7609: component set log level `#78`
- COR-7535: container resources `#77`
- COR-7627: docker image vendoring `#76`

#### Fixed

- Merge branch 'GIT-432-do-not-mount-k8s-api-token' into '1.1-dev' `#GIT-432` `#GIT-432` `#GIT-432`
- GIT-432: AutomountServiceAccountToken = false `#GIT-432`
- Merge branch 'DBCAL-151-describe-support-several-pods' into '1.1-dev' `#DBCAL-151` `#DBCAL-151` `#DBCAL-151` `#COR-8248` `#COR-7609` `#COR-7535` `#COR-7627`
- DBCALL-151: describe api: support list with several pods `#DBCALL-151`
- Merge branch 'COR-8767-add-kubecore-linter' into '1.1-dev' `#COR-8767` `#COR-8767` `#COR-8767`
- Merge branch 'COR-8691-change-clusterRole-apiVersion' into '1.1-dev' `#COR-8691` `#COR-8691` `#COR-8691`
- Merge branch 'COR-8717-validate-kube-resources' into '1.1-dev' `#COR-8717` `#COR-8717` `#COR-8717`
- Merge branch 'COR-8717-validate-kube-resources' into '1.1-dev' `#COR-8717` `#COR-8717` `#COR-8717`
- COR-8717: validate kube resources `#COR-8717`
- Merge branch 'COR-8248-generate-changelog' into '1.0-dev' `#COR-8248` `#COR-8248` `#COR-8248`
- COR-8248: "Generate changelog" `#COR-8248`
- Merge branch 'COR-7609_component_set_log_level' into '1.0-dev' `#COR-7609` `#COR-7609` `#COR-7609`
- COR-7609: component set log level `#COR-7609`
- Merge branch 'COR-7535_container_resources' into '1.0-dev' `#COR-7535` `#COR-7535` `#COR-7535`
- COR-7535: container resources `#COR-7535`
- Merge branch 'COR-7627_docker_image_vendoring' into '1.0-dev' `#COR-7627` `#COR-7627` `#COR-7627`
- COR-7627: docker image vendoring `#COR-7627`
- COR-6972: ad cluster_role_binding_name to helm schema `#COR-6972`
- COR-6972: add cluster role name to helm schema. `#COR-6972`

## gitcall.config.dundergitcall.global_policy.dundergitcall_image

### 2.0.1 - 2022-06-17

GIT-461: usercode v1 support

Closes GIT-461

See merge request gitcall/dunder-gitcall!116

#### Merged

- GIT-461: usercode v1 support `#116`

#### Fixed

- Merge branch 'GIT-461-usercode-v1-support' into '2.0-dev' `#GIT-461` `#GIT-461` `#GIT-461`
- GIT-461: usercode v1 support `#GIT-461`

### 2.0.0 - 2022-06-16

#### Merged

- GIT-448:  rpc-metrics `#115`
- GIT-451: update promapp, sentry, gopsagent; remove logrus `#114`
- GIT-449: move dunder-gitcall-sdk code to sdk dir `#113`
- GIT-437: use jsonrpc lib. simplify logic `#112`
- GIT-442: upd amqpextra lib `#111`
- GIT-441:  migrate to taskfile, upd ci `#110`
- COR-8688: update dundergitcallsdk module version `#109`
- fix-e2e-multihost-connection-test `#107`
- COR-8688: allow configure status update transports `#108`
- COR-8411: Send status udpates via http API `#103`

#### Fixed

- Merge branch 'GIT-448-rpc-metrics' into '2.0-dev' `#GIT-448` `#GIT-448` `#GIT-448`
- GIT-448: add retry metric `#GIT-448`
- GIT-448: move active_connections metric to usercode-proxy `#GIT-448`
- GIT-448-rpc-metrics `#GIT-448`
- Merge branch 'GIT-451-upd-promapp-sentry-gopsagent-packages' into '2.0-dev' `#GIT-451` `#GIT-451` `#GIT-451`
- GIT-451: update promapp, sentry, gopsagent; remove logrus `#GIT-451` `#GIT-449`
- Merge branch 'GIT-449-sdk' into '2.0-dev' `#GIT-449` `#GIT-449` `#GIT-449`
- GIT-449: move dunder-gitcall-sdk code to sdk dir `#GIT-449`
- Merge branch 'GIT-437-simplify-logic' into '2.0-dev' `#GIT-437` `#GIT-437` `#GIT-437`
- GIT-437: wip `#GIT-437`
- GIT-437: wip `#GIT-437`
- Merge branch 'GIT-442-upd-amqpextra' into '2.0-dev' `#GIT-442` `#GIT-442` `#GIT-442`
- GIT-442: switch to zlog in amqpextra logic. `#GIT-442`
- GIT-442: upd amqpextra lib `#GIT-442`
- Merge branch 'GIT-441-taskfile' into '2.0-dev' `#GIT-441` `#GIT-441` `#GIT-441`
- GIT-441: migrate func tests `#GIT-441`
- GIT-441: migrate to taskfile, upd ci `#GIT-441`
- Merge branch 'COR-8688-update-dundergitcallsdk-module' into '1.0-dev' `#COR-8688` `#COR-8688` `#COR-8688`
- Merge branch 'COR-8688-allow-configure-status-update-transports' into '1.0-dev' `#COR-8688` `#COR-8688` `#COR-8688`
- Merge branch 'COR-8411-udpates-via-http' into '1.0-dev' `#COR-8411` `#COR-8411` `#COR-8411`
- COR-8411: Send status udpates via http API `#COR-8411`

## gitcall.config.dundergitcall.global_policy.usercode_js_runner_image

No changes

## gitcall.config.dundergitcall.global_policy.usercode_php_runner_image

No changes

## gitcall.config.dundergitcall.global_policy.usercode_proxy_image

### 2.0.1 - 2022-06-17

#### Commits

- cleanup `c717ad0`

### 2.0.0 - 2022-06-15

#### Merged

- GIT-456: upd packages `#25`
- GIT-448: add io autoscale metrics `#24`
- GIT-454: reset deadline after call, upd jsonrpc client `#23`
- GIT-455: task options `#22`
- GIT-447: java docker args buggy. a workaround fix `#21`
- GIT-447: pass env vars, fix java code `#20`
- Endless code test and fix `#19`
- GIT-446: usercode busy `#18`
- GIT-445: upd jsonrpc lib `#17`
- GIT-440: result max size `#16`
- GIT-436: proxy using new logic `#15`
- GIT-419: jsonrpc server\client `#14`
- GIT-435: upd CI scripts `#13`

#### Fixed

- Merge branch 'GIT-456-upd-packages' into '2.0-dev' `#GIT-456` `#GIT-456`
- Merge branch '2.0-dev' into GIT-456-upd-packages `#GIT-456`
- Merge branch 'GIT-448-add-io-autoscale-metrics' into '2.0-dev' `#GIT-448` `#GIT-448`
- GIT-448: ignore too big waitTimeoutMs, timeoutMs `#GIT-448`
- GIT-448: port usercode metrics from dundergitcall `#GIT-448`
- Merge branch 'GIT-454-reset-deadline-after-call' into '2.0-dev' `#GIT-454` `#GIT-454`
- GIT-454: reset deadline after call, upd jsonrpc client `#GIT-454`
- Merge branch 'GIT-455-task-options' into '2.0-dev' `#GIT-455` `#GIT-455`
- GIT-455: task options `#GIT-455`
- Merge branch 'GIT-447-java-specific-fix' into '2.0-dev' `#GIT-447` `#GIT-447`
- GIT-447: java docker args buggy. a workaround fix `#GIT-447`
- Merge branch 'GIT-447-pass-envs' into '2.0-dev' `#GIT-447` `#GIT-447`
- GIT-447: fix java args `#GIT-447`
- GIT-447: pass env vars, fix java code `#GIT-447`
- Merge branch 'GIT-446-usercode-busy' into '2.0-dev' `#GIT-446` `#GIT-446`
- GIT-446: usercode busy `#GIT-446`
- Merge branch 'GIT-445-upd-jsonrpc-lib' into '2.0-dev' `#GIT-445` `#GIT-445`
- GIT-445: upd jsonrpc lib `#GIT-445`
- Merge branch 'GIT-440-task-result-size' into '2.0-dev' `#GIT-440` `#GIT-440`
- GIT-440: result max size `#GIT-440`
- Merge branch 'GIT-436-proxy-using-std-client' into '2.0-dev' `#GIT-436` `#GIT-436`
- GIT-436: deamon improvements, simpifications `#GIT-436`
- GIT-436: working version `#GIT-436`
- GIT-436: proxy using new logic `#GIT-436`
- Merge branch 'GIT-419-std-json-rpc-server' into '1.2-dev' `#GIT-419` `#GIT-419`
- GIT-419: jsonrpc client with a pool of connections. `#GIT-419`
- GIT-419: jsonrpc server with graceful stop `#GIT-419`
- Merge branch '1.1-dev' into GIT-419-std-json-rpc-server `#GIT-419`
- Merge branch 'GIT-435-upd-ci-scripts' into '1.1-dev' `#GIT-435` `#GIT-435`
- GIT-435: upd CI scripts `#GIT-435`

## gitcall.config.dundergitcall.global_policy.usercode_python_runner_image

No changes

## gitcall.config.dundergitcall.global_policy.usercode_java_runner_image

No changes

