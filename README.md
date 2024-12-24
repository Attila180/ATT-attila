2024-12-03T18:22:50.8841756Z Current runner version: '2.321.0'
2024-12-03T18:22:50.8889367Z ##[group]Operating System
2024-12-03T18:22:50.8890237Z Ubuntu
2024-12-03T18:22:50.8890694Z 22.04.5
2024-12-03T18:22:50.8891190Z LTS
2024-12-03T18:22:50.8891757Z ##[endgroup]
2024-12-03T18:22:50.8892678Z ##[group]Runner Image
2024-12-03T18:22:50.8893278Z Image: ubuntu-22.04
2024-12-03T18:22:50.8893873Z Version: 20241124.1.0
2024-12-03T18:22:50.8894868Z Included Software: https://github.com/actions/runner-images/blob/ubuntu22/20241124.1/images/ubuntu/Ubuntu2204-Readme.md
2024-12-03T18:22:50.8896268Z Image Release: https://github.com/actions/runner-images/releases/tag/ubuntu22%2F20241124.1
2024-12-03T18:22:50.8897235Z ##[endgroup]
2024-12-03T18:22:50.8897732Z ##[group]Runner Image Provisioner
2024-12-03T18:22:50.8898326Z 2.0.385.1
2024-12-03T18:22:50.8898854Z ##[endgroup]
2024-12-03T18:22:50.8900984Z ##[group]GITHUB_TOKEN Permissions
2024-12-03T18:22:50.8903198Z Actions: read
2024-12-03T18:22:50.8903928Z Attestations: read
2024-12-03T18:22:50.8904645Z Checks: read
2024-12-03T18:22:50.8905104Z Contents: read
2024-12-03T18:22:50.8905619Z Deployments: read
2024-12-03T18:22:50.8906200Z Discussions: read
2024-12-03T18:22:50.8906668Z Issues: read
2024-12-03T18:22:50.8907157Z Metadata: read
2024-12-03T18:22:50.8907713Z Packages: read
2024-12-03T18:22:50.8908171Z Pages: read
2024-12-03T18:22:50.8908670Z PullRequests: read
2024-12-03T18:22:50.8909287Z RepositoryProjects: read
2024-12-03T18:22:50.8909804Z SecurityEvents: read
2024-12-03T18:22:50.8910333Z Statuses: read
2024-12-03T18:22:50.8910880Z ##[endgroup]
2024-12-03T18:22:50.8913106Z Secret source: Dependabot
2024-12-03T18:22:50.8913887Z Prepare workflow directory
2024-12-03T18:22:50.9288513Z Prepare all required actions
2024-12-03T18:22:50.9325979Z Getting action download info
2024-12-03T18:22:51.1300721Z Download action repository 'actions/checkout@v4' (SHA:11bd71901bbe5b1630ceea73d27597364c9af683)
2024-12-03T18:22:51.2425882Z Download action repository 'actions/setup-node@v4' (SHA:39370e3970a6d050c480ffad4ff0ed4d3fdee5af)
2024-12-03T18:22:51.4016314Z Complete job name: Type Check
2024-12-03T18:22:51.4849067Z ##[group]Run actions/checkout@v4
2024-12-03T18:22:51.4850723Z with:
2024-12-03T18:22:51.4851545Z   repository: coinbase/coinbase-wallet-sdk
2024-12-03T18:22:51.4853288Z   token: ***
2024-12-03T18:22:51.4854187Z   ssh-strict: true
2024-12-03T18:22:51.4855032Z   ssh-user: git
2024-12-03T18:22:51.4855830Z   persist-credentials: true
2024-12-03T18:22:51.4856776Z   clean: true
2024-12-03T18:22:51.4857548Z   sparse-checkout-cone-mode: true
2024-12-03T18:22:51.4858477Z   fetch-depth: 1
2024-12-03T18:22:51.4859355Z   fetch-tags: false
2024-12-03T18:22:51.4860124Z   show-progress: true
2024-12-03T18:22:51.4860943Z   lfs: false
2024-12-03T18:22:51.4861833Z   submodules: false
2024-12-03T18:22:51.4862605Z   set-safe-directory: true
2024-12-03T18:22:51.4863983Z ##[endgroup]
2024-12-03T18:22:51.7370461Z Syncing repository: coinbase/coinbase-wallet-sdk
2024-12-03T18:22:51.7373510Z ##[group]Getting Git version info
2024-12-03T18:22:51.7374961Z Working directory is '/home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk'
2024-12-03T18:22:51.7376737Z [command]/usr/bin/git version
2024-12-03T18:22:51.7490506Z git version 2.47.0
2024-12-03T18:22:51.7522138Z ##[endgroup]
2024-12-03T18:22:51.7535295Z Temporarily overriding HOME='/home/runner/work/_temp/439c487c-4a8e-4a74-b030-4448511687f3' before making global git config changes
2024-12-03T18:22:51.7537039Z Adding repository directory to the temporary git global config as a safe directory
2024-12-03T18:22:51.7540718Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk
2024-12-03T18:22:51.7578199Z Deleting the contents of '/home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk'
2024-12-03T18:22:51.7582068Z ##[group]Initializing the repository
2024-12-03T18:22:51.7585660Z [command]/usr/bin/git init /home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk
2024-12-03T18:22:51.7667107Z hint: Using 'master' as the name for the initial branch. This default branch name
2024-12-03T18:22:51.7668954Z hint: is subject to change. To configure the initial branch name to use in all
2024-12-03T18:22:51.7670051Z hint: of your new repositories, which will suppress this warning, call:
2024-12-03T18:22:51.7671179Z hint:
2024-12-03T18:22:51.7671793Z hint: 	git config --global init.defaultBranch <name>
2024-12-03T18:22:51.7672515Z hint:
2024-12-03T18:22:51.7673137Z hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
2024-12-03T18:22:51.7675288Z hint: 'development'. The just-created branch can be renamed via this command:
2024-12-03T18:22:51.7676771Z hint:
2024-12-03T18:22:51.7677500Z hint: 	git branch -m <name>
2024-12-03T18:22:51.7679085Z Initialized empty Git repository in /home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk/.git/
2024-12-03T18:22:51.7688662Z [command]/usr/bin/git remote add origin https://github.com/coinbase/coinbase-wallet-sdk
2024-12-03T18:22:51.7728344Z ##[endgroup]
2024-12-03T18:22:51.7729899Z ##[group]Disabling automatic garbage collection
2024-12-03T18:22:51.7731728Z [command]/usr/bin/git config --local gc.auto 0
2024-12-03T18:22:51.7763689Z ##[endgroup]
2024-12-03T18:22:51.7764559Z ##[group]Setting up auth
2024-12-03T18:22:51.7769861Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2024-12-03T18:22:51.7800571Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2024-12-03T18:22:51.8148124Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2024-12-03T18:22:51.8177469Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2024-12-03T18:22:51.8417209Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2024-12-03T18:22:51.8454824Z ##[endgroup]
2024-12-03T18:22:51.8456148Z ##[group]Fetching the repository
2024-12-03T18:22:51.8463160Z [command]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --no-recurse-submodules --depth=1 origin +3a7e4ddd91e878300489c25c894f8cca86699ab5:refs/remotes/pull/1454/merge
2024-12-03T18:22:52.2531553Z From https://github.com/coinbase/coinbase-wallet-sdk
2024-12-03T18:22:52.2533717Z  * [new ref]         3a7e4ddd91e878300489c25c894f8cca86699ab5 -> pull/1454/merge
2024-12-03T18:22:52.2562558Z ##[endgroup]
2024-12-03T18:22:52.2564208Z ##[group]Determining the checkout info
2024-12-03T18:22:52.2566394Z ##[endgroup]
2024-12-03T18:22:52.2569026Z [command]/usr/bin/git sparse-checkout disable
2024-12-03T18:22:52.2615308Z [command]/usr/bin/git config --local --unset-all extensions.worktreeConfig
2024-12-03T18:22:52.2646019Z ##[group]Checking out the ref
2024-12-03T18:22:52.2650207Z [command]/usr/bin/git checkout --progress --force refs/remotes/pull/1454/merge
2024-12-03T18:22:52.2955724Z Note: switching to 'refs/remotes/pull/1454/merge'.
2024-12-03T18:22:52.2958741Z 
2024-12-03T18:22:52.2959680Z You are in 'detached HEAD' state. You can look around, make experimental
2024-12-03T18:22:52.2962057Z changes and commit them, and you can discard any commits you make in this
2024-12-03T18:22:52.2964264Z state without impacting any branches by switching back to a branch.
2024-12-03T18:22:52.2965520Z 
2024-12-03T18:22:52.2966591Z If you want to create a new branch to retain commits you create, you may
2024-12-03T18:22:52.2968590Z do so (now or later) by using -c with the switch command. Example:
2024-12-03T18:22:52.2969728Z 
2024-12-03T18:22:52.2970274Z   git switch -c <new-branch-name>
2024-12-03T18:22:52.2971116Z 
2024-12-03T18:22:52.2971849Z Or undo this operation with:
2024-12-03T18:22:52.2972964Z 
2024-12-03T18:22:52.2973516Z   git switch -
2024-12-03T18:22:52.2974278Z 
2024-12-03T18:22:52.2975287Z Turn off this advice by setting config variable advice.detachedHead to false
2024-12-03T18:22:52.2977188Z 
2024-12-03T18:22:52.2979263Z HEAD is now at 3a7e4dd Merge 031eabec262efb5d78cd9eb82d65ea40fc100a3b into e6978b87612f828d11c52b121e9b3a50ffb5abdd
2024-12-03T18:22:52.2984708Z ##[endgroup]
2024-12-03T18:22:52.3005754Z [command]/usr/bin/git log -1 --format=%H
2024-12-03T18:22:52.3030681Z 3a7e4ddd91e878300489c25c894f8cca86699ab5
2024-12-03T18:22:52.3335419Z ##[group]Run actions/setup-node@v4
2024-12-03T18:22:52.3336629Z with:
2024-12-03T18:22:52.3337637Z   node-version-file: .nvmrc
2024-12-03T18:22:52.3338700Z   cache-dependency-path: **/yarn.lock
2024-12-03T18:22:52.3339871Z   always-auth: false
2024-12-03T18:22:52.3340923Z   check-latest: false
2024-12-03T18:22:52.3342214Z   token: ***
2024-12-03T18:22:52.3343120Z ##[endgroup]
2024-12-03T18:22:52.4967970Z Node version file is not JSON file
2024-12-03T18:22:52.4970203Z Resolved .nvmrc as 18.20.4
2024-12-03T18:22:52.4980769Z Attempting to download 18.20.4...
2024-12-03T18:22:52.9938998Z Acquiring 18.20.4 - x64 from https://github.com/actions/node-versions/releases/download/18.20.4-9860952736/node-18.20.4-linux-x64.tar.gz
2024-12-03T18:22:53.4426482Z Extracting ...
2024-12-03T18:22:53.4530783Z [command]/usr/bin/tar xz --strip 1 --warning=no-unknown-keyword --overwrite -C /home/runner/work/_temp/b7839b08-d6aa-465b-bc5b-b005da8a057e -f /home/runner/work/_temp/75422fa0-99d9-4852-a5fe-d936a7111079
2024-12-03T18:22:54.4068982Z Adding to the cache ...
2024-12-03T18:22:55.9419618Z ##[group]Environment details
2024-12-03T18:22:56.5460010Z node: v18.20.4
2024-12-03T18:22:56.5460626Z npm: 10.7.0
2024-12-03T18:22:56.5461130Z yarn: 3.6.1
2024-12-03T18:22:56.5462030Z ##[endgroup]
2024-12-03T18:22:56.5630323Z ##[group]Run yarn install --immutable
2024-12-03T18:22:56.5630821Z [36;1myarn install --immutable[0m
2024-12-03T18:22:56.5736621Z shell: /usr/bin/bash -e {0}
2024-12-03T18:22:56.5737104Z ##[endgroup]
2024-12-03T18:22:57.2280283Z [94m➤[39m [90mYN0000[39m: ┌ Resolution step
2024-12-03T18:22:57.2281451Z ##[group]Resolution step
2024-12-03T18:22:57.4324478Z [93m➤[39m YN0060: │ [38;5;166m@coinbase/[39m[38;5;173mwallet-sdk[39m[38;5;111m@[39m[38;5;111mworkspace:packages/wallet-sdk[39m provides [38;5;166m@types/[39m[38;5;173mnode[39m ([38;5;111mpbf606[39m) with version [38;5;111m14.18.63[39m, which doesn't satisfy what [38;5;173mvitest[39m and some of its descendants request
2024-12-03T18:22:57.4328832Z [93m➤[39m YN0002: │ [38;5;173msdk-playground[39m[38;5;111m@[39m[38;5;111mworkspace:examples/testapp[39m doesn't provide [38;5;166m@chakra-ui/[39m[38;5;173msystem[39m ([38;5;111mpea1e9[39m), requested by [38;5;166m@chakra-ui/[39m[38;5;173micons[39m
2024-12-03T18:22:57.4332601Z [93m➤[39m YN0000: │ Some peer dependencies are incorrectly met; run [38;5;111myarn explain peer-requirements <hash>[39m for details, where [38;5;111m<hash>[39m is the six-letter p-prefixed code
2024-12-03T18:22:57.4377931Z ##[endgroup]
2024-12-03T18:22:57.4379140Z [94m➤[39m [90mYN0000[39m: └ Completed in 0s 210ms
2024-12-03T18:22:57.4964235Z [94m➤[39m [90mYN0000[39m: ┌ Fetch step
2024-12-03T18:22:57.4965748Z ##[group]Fetch step
2024-12-03T18:23:21.0944942Z [93m➤[39m YN0066: │ [38;5;173mtypescript[39m[38;5;111m@[39m[38;5;111mpatch:typescript@npm%3A5.6.2#~builtin<compat/typescript>::version=5.6.2&hash=14eedb[39m: Cannot apply hunk #1
2024-12-03T18:23:32.2682788Z [94m➤[39m YN0013: │ 49 packages were already cached, 921 had to be fetched
2024-12-03T18:23:32.2715376Z ##[endgroup]
2024-12-03T18:23:32.2716446Z [94m➤[39m [90mYN0000[39m: └ Completed in 34s 775ms
2024-12-03T18:23:32.3163229Z [94m➤[39m [90mYN0000[39m: ┌ Link step
2024-12-03T18:23:32.3172654Z ##[group]Link step
2024-12-03T18:23:42.8749687Z [94m➤[39m YN0007: │ [38;5;173mkeccak[39m[38;5;111m@[39m[38;5;111mnpm:3.0.4[39m must be built because it never has been before or the last one failed
2024-12-03T18:23:42.8753579Z [94m➤[39m YN0007: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m must be built because it never has been before or the last one failed
2024-12-03T18:23:42.8756653Z [94m➤[39m YN0007: │ [38;5;173mesbuild[39m[38;5;111m@[39m[38;5;111mnpm:0.21.5[39m must be built because it never has been before or the last one failed
2024-12-03T18:23:42.8758763Z [94m➤[39m YN0007: │ [38;5;173mbufferutil[39m[38;5;111m@[39m[38;5;111mnpm:4.0.8[39m must be built because it never has been before or the last one failed
2024-12-03T18:23:42.8761082Z [94m➤[39m YN0007: │ [38;5;173mutf-8-validate[39m[38;5;111m@[39m[38;5;111mnpm:5.0.10[39m must be built because it never has been before or the last one failed
2024-12-03T18:23:43.3206688Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [32mSTDOUT[39m 
2024-12-03T18:23:43.3208658Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [32mSTDOUT[39m > bigint-buffer@1.1.5 rebuild
2024-12-03T18:23:43.3210888Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [32mSTDOUT[39m > node-gyp rebuild
2024-12-03T18:23:43.3213013Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [32mSTDOUT[39m 
2024-12-03T18:23:43.3635121Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info it worked if it ends with ok
2024-12-03T18:23:43.3637658Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info using node-gyp@10.2.0
2024-12-03T18:23:43.3640197Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info using node@18.20.4 | linux | x64
2024-12-03T18:23:43.4331148Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info find Python using Python version 3.10.12 found at "/usr/bin/python3"
2024-12-03T18:23:43.5349897Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [32mSTDOUT[39m 
2024-12-03T18:23:43.5366850Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp http GET https://nodejs.org/download/release/v18.20.4/node-v18.20.4-headers.tar.gz
2024-12-03T18:23:43.6380381Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp http 200 https://nodejs.org/download/release/v18.20.4/node-v18.20.4-headers.tar.gz
2024-12-03T18:23:44.7602729Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp http GET https://nodejs.org/download/release/v18.20.4/SHASUMS256.txt
2024-12-03T18:23:44.7916359Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp http 200 https://nodejs.org/download/release/v18.20.4/SHASUMS256.txt
2024-12-03T18:23:44.7965897Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn /usr/bin/python3
2024-12-03T18:23:44.7985272Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args [
2024-12-03T18:23:44.7990762Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '/home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk/node_modules/node-gyp/gyp/gyp_main.py',
2024-12-03T18:23:44.7993257Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args 'binding.gyp',
2024-12-03T18:23:44.7994710Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '-f',
2024-12-03T18:23:44.7996060Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args 'make',
2024-12-03T18:23:44.7997870Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '-I',
2024-12-03T18:23:44.8000905Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '/home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk/node_modules/bigint-buffer/build/config.gypi',
2024-12-03T18:23:44.8003528Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '-I',
2024-12-03T18:23:44.8006238Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '/home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk/node_modules/node-gyp/addon.gypi',
2024-12-03T18:23:44.8008850Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '-I',
2024-12-03T18:23:44.8011294Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '/home/runner/.cache/node-gyp/18.20.4/include/node/common.gypi',
2024-12-03T18:23:44.8014583Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '-Dlibrary=shared_library',
2024-12-03T18:23:44.8017114Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '-Dvisibility=default',
2024-12-03T18:23:44.8019739Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '-Dnode_root_dir=/home/runner/.cache/node-gyp/18.20.4',
2024-12-03T18:23:44.8022965Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '-Dnode_gyp_dir=/home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk/node_modules/node-gyp',
2024-12-03T18:23:44.8025908Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '-Dnode_lib_file=/home/runner/.cache/node-gyp/18.20.4/<(target_arch)/node.lib',
2024-12-03T18:23:44.8027979Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '-Dmodule_root_dir=/home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk/node_modules/bigint-buffer',
2024-12-03T18:23:44.8029436Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '-Dnode_engine=v8',
2024-12-03T18:23:44.8030704Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '--depth=.',
2024-12-03T18:23:44.8031798Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '--no-parallel',
2024-12-03T18:23:44.8032995Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '--generator-output',
2024-12-03T18:23:44.8034084Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args 'build',
2024-12-03T18:23:44.8035774Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args '-Goutput_dir=.'
2024-12-03T18:23:44.8037968Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args ]
2024-12-03T18:23:44.9028548Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn make
2024-12-03T18:23:44.9029801Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info spawn args [ 'BUILDTYPE=Release', '-C', 'build' ]
2024-12-03T18:23:44.9045800Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [32mSTDOUT[39m make: Entering directory '/home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk/node_modules/bigint-buffer/build'
2024-12-03T18:23:44.9062614Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [32mSTDOUT[39m   CC(target) Release/obj.target/bigint_buffer/src/bigint-buffer.o
2024-12-03T18:23:45.1219035Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [32mSTDOUT[39m   SOLINK_MODULE(target) Release/obj.target/bigint_buffer.node
2024-12-03T18:23:45.1657305Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [32mSTDOUT[39m   COPY Release/bigint_buffer.node
2024-12-03T18:23:45.1698959Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [32mSTDOUT[39m make: Leaving directory '/home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk/node_modules/bigint-buffer/build'
2024-12-03T18:23:45.1712840Z [94m➤[39m [90mYN0000[39m: │ [38;5;173mbigint-buffer[39m[38;5;111m@[39m[38;5;111mnpm:1.1.5[39m [31mSTDERR[39m gyp info ok 
2024-12-03T18:23:45.1891805Z ##[endgroup]
2024-12-03T18:23:45.1893046Z [94m➤[39m [90mYN0000[39m: └ Completed in 12s 872ms
2024-12-03T18:23:45.2541517Z [93m➤[39m YN0000: Done with warnings in 48s 32ms
2024-12-03T18:23:45.4275476Z ##[group]Run node ./compile-assets.cjs
2024-12-03T18:23:45.4276040Z [36;1mnode ./compile-assets.cjs[0m
2024-12-03T18:23:45.4334231Z shell: /usr/bin/bash -e {0}
2024-12-03T18:23:45.4334695Z ##[endgroup]
2024-12-03T18:23:45.6812690Z Compiling /home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk/packages/wallet-sdk/src/sign/walletlink/relay/ui/components/cssReset/cssReset.scss...
2024-12-03T18:23:45.7279170Z Compiling /home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk/packages/wallet-sdk/src/sign/walletlink/relay/ui/components/Snackbar/Snackbar.scss...
2024-12-03T18:23:45.7476151Z Compiling /home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk/packages/wallet-sdk/src/sign/walletlink/relay/ui/components/RedirectDialog/RedirectDialog.scss...
2024-12-03T18:23:45.7532266Z DONE!
2024-12-03T18:23:45.7701666Z ##[group]Run yarn typecheck
2024-12-03T18:23:45.7702105Z [36;1myarn typecheck[0m
2024-12-03T18:23:45.7759114Z shell: /usr/bin/bash -e {0}
2024-12-03T18:23:45.7759425Z ##[endgroup]
2024-12-03T18:23:49.1092461Z Post job cleanup.
2024-12-03T18:23:49.2675082Z Post job cleanup.
2024-12-03T18:23:49.3614549Z [command]/usr/bin/git version
2024-12-03T18:23:49.3656723Z git version 2.47.0
2024-12-03T18:23:49.3697441Z Temporarily overriding HOME='/home/runner/work/_temp/b1e9e2f6-5239-4003-b34d-ed99b4589472' before making global git config changes
2024-12-03T18:23:49.3698591Z Adding repository directory to the temporary git global config as a safe directory
2024-12-03T18:23:49.3702520Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/coinbase-wallet-sdk/coinbase-wallet-sdk
2024-12-03T18:23:49.3740308Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2024-12-03T18:23:49.3774896Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2024-12-03T18:23:49.4015092Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2024-12-03T18:23:49.4038202Z http.https://github.com/.extraheader
2024-12-03T18:23:49.4048953Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2024-12-03T18:23:49.4082762Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2024-12-03T18:23:49.4427689Z Cleaning up orphan processes
