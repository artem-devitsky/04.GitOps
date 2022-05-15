# 04.GitOps
##Link to repo:
	https://github.com/artem-devitsky/04.GitOps
##Link to file: 
	https://github.com/artem-devitsky/04.GitOps/blob/dev/find_tabs_pr.yaml
##Pipeline Log:
```bash
2022-05-15T12:47:35.9902213Z Requested labels: ubuntu-latest
2022-05-15T12:47:35.9902311Z Job defined at: artem-devitsky/04.GitOps/.github/workflows/find_tabs_push.yaml@refs/heads/dev
2022-05-15T12:47:35.9902332Z Waiting for a runner to pick up this job...
2022-05-15T12:47:36.3669182Z Job is waiting for a hosted runner to come online.
2022-05-15T12:47:40.8341441Z Job is about to start running on the hosted runner: Hosted Agent (hosted)
2022-05-15T12:47:42.7394631Z Current runner version: '2.291.1'
2022-05-15T12:47:42.7420640Z ##[group]Operating System
2022-05-15T12:47:42.7421316Z Ubuntu
2022-05-15T12:47:42.7421584Z 20.04.4
2022-05-15T12:47:42.7421899Z LTS
2022-05-15T12:47:42.7422242Z ##[endgroup]
2022-05-15T12:47:42.7422561Z ##[group]Virtual Environment
2022-05-15T12:47:42.7423010Z Environment: ubuntu-20.04
2022-05-15T12:47:42.7423380Z Version: 20220508.1
2022-05-15T12:47:42.7423976Z Included Software: https://github.com/actions/virtual-environments/blob/ubuntu20/20220508.1/images/linux/Ubuntu2004-Readme.md
2022-05-15T12:47:42.7424697Z Image Release: https://github.com/actions/virtual-environments/releases/tag/ubuntu20%2F20220508.1
2022-05-15T12:47:42.7425244Z ##[endgroup]
2022-05-15T12:47:42.7425642Z ##[group]Virtual Environment Provisioner
2022-05-15T12:47:42.7426113Z 1.0.0.0-main-20220421-1
2022-05-15T12:47:42.7426430Z ##[endgroup]
2022-05-15T12:47:42.7427006Z ##[group]GITHUB_TOKEN Permissions
2022-05-15T12:47:42.7427590Z Contents: read
2022-05-15T12:47:42.7428027Z Metadata: read
2022-05-15T12:47:42.7428350Z ##[endgroup]
2022-05-15T12:47:42.7431988Z Secret source: Actions
2022-05-15T12:47:42.7432741Z Prepare workflow directory
2022-05-15T12:47:42.8218435Z Prepare all required actions
2022-05-15T12:47:42.8394774Z Getting action download info
2022-05-15T12:47:43.0278897Z Download action repository 'actions/checkout@v2' (SHA:7884fcad6b5d53d10323aee724dc68d8b9096a2e)
2022-05-15T12:47:43.3296814Z Download action repository 'tj-actions/changed-files@v19' (SHA:a6d456f542692915c5289ea834fb89bc07c11208)
2022-05-15T12:47:43.5190419Z Download action repository 'actions/upload-artifact@v2' (SHA:82c141cc518b40d92cc801eee768e7aafc9c2fa2)
2022-05-15T12:47:43.8185519Z Getting action download info
2022-05-15T12:47:43.9455019Z Download action repository 'tj-actions/glob@v7.16' (SHA:7e147c5f2fb842ce53357a35f14589222ee81b7f)
2022-05-15T12:47:44.2992217Z ##[group]Run actions/checkout@v2
2022-05-15T12:47:44.2992513Z with:
2022-05-15T12:47:44.2992746Z   fetch-depth: 0
2022-05-15T12:47:44.2993035Z   repository: artem-devitsky/04.GitOps
2022-05-15T12:47:44.2993552Z   token: ***
2022-05-15T12:47:44.2993762Z   ssh-strict: true
2022-05-15T12:47:44.2994026Z   persist-credentials: true
2022-05-15T12:47:44.2994277Z   clean: true
2022-05-15T12:47:44.2994474Z   lfs: false
2022-05-15T12:47:44.2994693Z   submodules: false
2022-05-15T12:47:44.2994958Z   set-safe-directory: true
2022-05-15T12:47:44.2995201Z ##[endgroup]
2022-05-15T12:47:44.5936163Z Syncing repository: artem-devitsky/04.GitOps
2022-05-15T12:47:44.5937949Z ##[group]Getting Git version info
2022-05-15T12:47:44.5938488Z Working directory is '/home/runner/work/04.GitOps/04.GitOps'
2022-05-15T12:47:44.5939026Z [command]/usr/bin/git version
2022-05-15T12:47:44.6093234Z git version 2.36.1
2022-05-15T12:47:44.6094159Z ##[endgroup]
2022-05-15T12:47:44.6112449Z Temporarily overriding HOME='/home/runner/work/_temp/0ea774e2-7130-416d-9e9e-0bb1e29c2be9' before making global git config changes
2022-05-15T12:47:44.6113014Z Adding repository directory to the temporary git global config as a safe directory
2022-05-15T12:47:44.6119953Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/04.GitOps/04.GitOps
2022-05-15T12:47:44.6161564Z Deleting the contents of '/home/runner/work/04.GitOps/04.GitOps'
2022-05-15T12:47:44.6165822Z ##[group]Initializing the repository
2022-05-15T12:47:44.6169980Z [command]/usr/bin/git init /home/runner/work/04.GitOps/04.GitOps
2022-05-15T12:47:44.6243513Z hint: Using 'master' as the name for the initial branch. This default branch name
2022-05-15T12:47:44.6244234Z hint: is subject to change. To configure the initial branch name to use in all
2022-05-15T12:47:44.6245189Z hint: of your new repositories, which will suppress this warning, call:
2022-05-15T12:47:44.6245575Z hint: 
2022-05-15T12:47:44.6246090Z hint: 	git config --global init.defaultBranch <name>
2022-05-15T12:47:44.6246376Z hint: 
2022-05-15T12:47:44.6246759Z hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
2022-05-15T12:47:44.6247453Z hint: 'development'. The just-created branch can be renamed via this command:
2022-05-15T12:47:44.6247760Z hint: 
2022-05-15T12:47:44.6248026Z hint: 	git branch -m <name>
2022-05-15T12:47:44.6263995Z Initialized empty Git repository in /home/runner/work/04.GitOps/04.GitOps/.git/
2022-05-15T12:47:44.6275262Z [command]/usr/bin/git remote add origin https://github.com/artem-devitsky/04.GitOps
2022-05-15T12:47:44.6354883Z ##[endgroup]
2022-05-15T12:47:44.6355817Z ##[group]Disabling automatic garbage collection
2022-05-15T12:47:44.6359418Z [command]/usr/bin/git config --local gc.auto 0
2022-05-15T12:47:44.6394780Z ##[endgroup]
2022-05-15T12:47:44.6395650Z ##[group]Setting up auth
2022-05-15T12:47:44.6403417Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2022-05-15T12:47:44.6438669Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2022-05-15T12:47:44.6827687Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2022-05-15T12:47:44.6883790Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
2022-05-15T12:47:44.7168968Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2022-05-15T12:47:44.7169671Z ##[endgroup]
2022-05-15T12:47:44.7170135Z ##[group]Fetching the repository
2022-05-15T12:47:44.7171373Z [command]/usr/bin/git -c protocol.version=2 fetch --prune --progress --no-recurse-submodules origin +refs/heads/*:refs/remotes/origin/* +refs/tags/*:refs/tags/*
2022-05-15T12:47:44.9330267Z remote: Enumerating objects: 17, done.        
2022-05-15T12:47:44.9364874Z remote: Counting objects:   5% (1/17)        
2022-05-15T12:47:44.9365869Z remote: Counting objects:  11% (2/17)        
2022-05-15T12:47:44.9366666Z remote: Counting objects:  17% (3/17)        
2022-05-15T12:47:44.9368092Z remote: Counting objects:  23% (4/17)        
2022-05-15T12:47:44.9368495Z remote: Counting objects:  29% (5/17)        
2022-05-15T12:47:44.9368866Z remote: Counting objects:  35% (6/17)        
2022-05-15T12:47:44.9369252Z remote: Counting objects:  41% (7/17)        
2022-05-15T12:47:44.9369634Z remote: Counting objects:  47% (8/17)        
2022-05-15T12:47:44.9370021Z remote: Counting objects:  52% (9/17)        
2022-05-15T12:47:44.9370395Z remote: Counting objects:  58% (10/17)        
2022-05-15T12:47:44.9371038Z remote: Counting objects:  64% (11/17)        
2022-05-15T12:47:44.9371435Z remote: Counting objects:  70% (12/17)        
2022-05-15T12:47:44.9371806Z remote: Counting objects:  76% (13/17)        
2022-05-15T12:47:44.9372200Z remote: Counting objects:  82% (14/17)        
2022-05-15T12:47:44.9372588Z remote: Counting objects:  88% (15/17)        
2022-05-15T12:47:44.9372953Z remote: Counting objects:  94% (16/17)        
2022-05-15T12:47:44.9373335Z remote: Counting objects: 100% (17/17)        
2022-05-15T12:47:44.9373733Z remote: Counting objects: 100% (17/17), done.        
2022-05-15T12:47:44.9374427Z remote: Compressing objects:   8% (1/12)        
2022-05-15T12:47:44.9374848Z remote: Compressing objects:  16% (2/12)        
2022-05-15T12:47:44.9375248Z remote: Compressing objects:  25% (3/12)        
2022-05-15T12:47:44.9375655Z remote: Compressing objects:  33% (4/12)        
2022-05-15T12:47:44.9376044Z remote: Compressing objects:  41% (5/12)        
2022-05-15T12:47:44.9376453Z remote: Compressing objects:  50% (6/12)        
2022-05-15T12:47:44.9376863Z remote: Compressing objects:  58% (7/12)        
2022-05-15T12:47:44.9377247Z remote: Compressing objects:  66% (8/12)        
2022-05-15T12:47:44.9377650Z remote: Compressing objects:  75% (9/12)        
2022-05-15T12:47:44.9378057Z remote: Compressing objects:  83% (10/12)        
2022-05-15T12:47:44.9378448Z remote: Compressing objects:  91% (11/12)        
2022-05-15T12:47:44.9379163Z remote: Compressing objects: 100% (12/12)        
2022-05-15T12:47:44.9379589Z remote: Compressing objects: 100% (12/12), done.        
2022-05-15T12:47:44.9380430Z remote: Total 17 (delta 1), reused 16 (delta 0), pack-reused 0        
2022-05-15T12:47:44.9451769Z From https://github.com/artem-devitsky/04.GitOps
2022-05-15T12:47:44.9452288Z  * [new branch]      dev        -> origin/dev
2022-05-15T12:47:44.9452948Z  * [new branch]      main       -> origin/main
2022-05-15T12:47:44.9489893Z [command]/usr/bin/git branch --list --remote origin/dev
2022-05-15T12:47:44.9521241Z   origin/dev
2022-05-15T12:47:44.9530955Z [command]/usr/bin/git rev-parse refs/remotes/origin/dev
2022-05-15T12:47:44.9567771Z 5e4eb4c1418a5bf7460dba1de098c586ca06f5aa
2022-05-15T12:47:44.9568508Z ##[endgroup]
2022-05-15T12:47:44.9569022Z ##[group]Determining the checkout info
2022-05-15T12:47:44.9569491Z ##[endgroup]
2022-05-15T12:47:44.9569923Z ##[group]Checking out the ref
2022-05-15T12:47:44.9575243Z [command]/usr/bin/git checkout --progress --force -B dev refs/remotes/origin/dev
2022-05-15T12:47:44.9626953Z Switched to a new branch 'dev'
2022-05-15T12:47:44.9630453Z branch 'dev' set up to track 'origin/dev'.
2022-05-15T12:47:44.9633908Z ##[endgroup]
2022-05-15T12:47:44.9680752Z [command]/usr/bin/git log -1 --format='%H'
2022-05-15T12:47:44.9711200Z '5e4eb4c1418a5bf7460dba1de098c586ca06f5aa'
2022-05-15T12:47:45.0112530Z ##[group]Run tj-actions/changed-files@v19
2022-05-15T12:47:45.0112975Z with:
2022-05-15T12:47:45.0113427Z   token: ***
2022-05-15T12:47:45.0113636Z   separator:  
2022-05-15T12:47:45.0113868Z   files_separator: 

2022-05-15T12:47:45.0114116Z   files_ignore_separator: 

2022-05-15T12:47:45.0114396Z   sha: 5e4eb4c1418a5bf7460dba1de098c586ca06f5aa
2022-05-15T12:47:45.0114691Z   since_last_remote_commit: false
2022-05-15T12:47:45.0114947Z   use_fork_point: false
2022-05-15T12:47:45.0115167Z   quotepath: true
2022-05-15T12:47:45.0115389Z ##[endgroup]
2022-05-15T12:47:45.0419433Z ##[group]Run # "Set base sha..."
2022-05-15T12:47:45.0419797Z [36;1m# "Set base sha..."[0m
2022-05-15T12:47:45.0420040Z [36;1mif [[ -n "" ]]; then[0m
2022-05-15T12:47:45.0420326Z [36;1m  echo "::set-output name=base_sha::"[0m
2022-05-15T12:47:45.0420713Z [36;1melif [[ "false" == "true" && "5377331ef1b5aa671f1d493e27dddded1dd6b8a4" != "0000000000000000000000000000000000000000" ]]; then[0m
2022-05-15T12:47:45.0421294Z [36;1m    echo "::set-output name=base_sha::5377331ef1b5aa671f1d493e27dddded1dd6b8a4"[0m
2022-05-15T12:47:45.0421592Z [36;1mfi[0m
2022-05-15T12:47:45.0480616Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2022-05-15T12:47:45.0480862Z ##[endgroup]
2022-05-15T12:47:45.0688905Z ##[group]Run # "Calculating the previous and current SHA..."
2022-05-15T12:47:45.0689412Z [36;1m# "Calculating the previous and current SHA..."[0m
2022-05-15T12:47:45.0689777Z [36;1mbash $GITHUB_ACTION_PATH/diff-sha.sh[0m
2022-05-15T12:47:45.0736722Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2022-05-15T12:47:45.0737314Z env:
2022-05-15T12:47:45.0737672Z   GITHUB_SERVER_URL: https://github.com
2022-05-15T12:47:45.0738076Z   GITHUB_REPOSITORY: artem-devitsky/04.GitOps
2022-05-15T12:47:45.0738384Z   GITHUB_BASE_REF: 
2022-05-15T12:47:45.0738694Z   GITHUB_HEAD_REF: 
2022-05-15T12:47:45.0739141Z   GITHUB_ACTION_PATH: /home/runner/work/_actions/tj-actions/changed-files/v19
2022-05-15T12:47:45.0739605Z   INPUT_SHA: 5e4eb4c1418a5bf7460dba1de098c586ca06f5aa
2022-05-15T12:47:45.0739918Z   INPUT_BASE_SHA: 
2022-05-15T12:47:45.0740483Z   INPUT_TOKEN: ***
2022-05-15T12:47:45.0740951Z   INPUT_PATH: 
2022-05-15T12:47:45.0741189Z   INPUT_USE_FORK_POINT: false
2022-05-15T12:47:45.0741479Z ##[endgroup]
2022-05-15T12:47:45.0830005Z ##[group]changed-files-diff-sha
2022-05-15T12:47:45.0830454Z Resolving repository path...
2022-05-15T12:47:45.0862464Z Setting up 'temp_changed_files' remote...
2022-05-15T12:47:45.0901990Z No 'temp_changed_files' remote found
2022-05-15T12:47:45.0902742Z Creating 'temp_changed_files' remote...
2022-05-15T12:47:45.0945217Z Getting HEAD SHA...
2022-05-15T12:47:45.3122757Z remote: Total 0 (delta 0), reused 0 (delta 0), pack-reused 0        
2022-05-15T12:47:45.3156121Z From https://github.com/artem-devitsky/04.GitOps
2022-05-15T12:47:45.3156727Z  * [new branch]      dev        -> temp_changed_files/dev
2022-05-15T12:47:45.3273593Z ##[endgroup]
2022-05-15T12:47:45.3339551Z ##[group]Run tj-actions/glob@v7.16
2022-05-15T12:47:45.3339831Z with:
2022-05-15T12:47:45.3340149Z   files-separator: 

2022-05-15T12:47:45.3340514Z   escape-paths: true
2022-05-15T12:47:45.3340810Z   excluded-files-separator: 

2022-05-15T12:47:45.3341225Z   base-sha: 5377331ef1b5aa671f1d493e27dddded1dd6b8a4
2022-05-15T12:47:45.3341636Z   sha: 5e4eb4c1418a5bf7460dba1de098c586ca06f5aa
2022-05-15T12:47:45.3341960Z   include-deleted-files: true
2022-05-15T12:47:45.3342323Z   separator: |
2022-05-15T12:47:45.3342784Z   files-from-source-file-separator: 

2022-05-15T12:47:45.3343128Z   excluded-files-from-source-file-separator: 

2022-05-15T12:47:45.3343505Z   follow-symbolic-links: true
2022-05-15T12:47:45.3343843Z   strip-top-level-dir: true
2022-05-15T12:47:45.3344083Z ##[endgroup]
2022-05-15T12:47:45.4063071Z [command]/usr/bin/git rev-parse --show-toplevel
2022-05-15T12:47:45.4120695Z /home/runner/work/04.GitOps/04.GitOps
2022-05-15T12:47:45.4139902Z [command]/usr/bin/git diff --diff-filter=D --name-only 5377331ef1b5aa671f1d493e27dddded1dd6b8a4 5e4eb4c1418a5bf7460dba1de098c586ca06f5aa
2022-05-15T12:47:45.4184152Z 
2022-05-15T12:47:45.4364791Z ##[group]Run bash $GITHUB_ACTION_PATH/entrypoint.sh
2022-05-15T12:47:45.4365102Z [36;1mbash $GITHUB_ACTION_PATH/entrypoint.sh[0m
2022-05-15T12:47:45.4442830Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2022-05-15T12:47:45.4443119Z env:
2022-05-15T12:47:45.4443426Z   GITHUB_ACTION_PATH: /home/runner/work/_actions/tj-actions/changed-files/v19
2022-05-15T12:47:45.4443759Z   INPUT_FILES_PATTERN_FILE: 
2022-05-15T12:47:45.4443999Z   INPUT_SEPARATOR:  
2022-05-15T12:47:45.4444240Z   INPUT_PATH: 
2022-05-15T12:47:45.4444533Z   INPUT_PREVIOUS_SHA: 5377331ef1b5aa671f1d493e27dddded1dd6b8a4
2022-05-15T12:47:45.4444881Z   INPUT_CURRENT_SHA: 5e4eb4c1418a5bf7460dba1de098c586ca06f5aa
2022-05-15T12:47:45.4445182Z   INPUT_TARGET_BRANCH: dev
2022-05-15T12:47:45.4445429Z   INPUT_CURRENT_BRANCH: dev
2022-05-15T12:47:45.4445663Z   INPUT_QUOTEPATH: true
2022-05-15T12:47:45.4445902Z ##[endgroup]
2022-05-15T12:47:45.4587656Z ##[group]changed-files
2022-05-15T12:47:45.4588278Z Resolving repository path...
2022-05-15T12:47:45.4589737Z Retrieving changes between 5377331ef1b5aa671f1d493e27dddded1dd6b8a4 (dev) → 5e4eb4c1418a5bf7460dba1de098c586ca06f5aa (dev)
2022-05-15T12:47:45.4590333Z Getting diff...
2022-05-15T12:47:45.8031549Z Added files: find_tabs_pr.yaml report.log
2022-05-15T12:47:45.8032345Z Copied files: 
2022-05-15T12:47:45.8033381Z Deleted files: 
2022-05-15T12:47:45.8034116Z Modified files: README.md
2022-05-15T12:47:45.8034499Z Renamed files: 
2022-05-15T12:47:45.8034897Z Type Changed files: 
2022-05-15T12:47:45.8035262Z Unmerged files: 
2022-05-15T12:47:45.8035582Z Unknown files: 
2022-05-15T12:47:45.8035962Z All changed and modified files: README.md find_tabs_pr.yaml report.log
2022-05-15T12:47:45.8036666Z All changed files: README.md find_tabs_pr.yaml report.log
2022-05-15T12:47:45.8037129Z All modified files: README.md find_tabs_pr.yaml report.log
2022-05-15T12:47:45.8042882Z ##[endgroup]
2022-05-15T12:47:45.8168510Z ##[group]Run for file_name in README.md find_tabs_pr.yaml report.log
2022-05-15T12:47:45.8168959Z [36;1mfor file_name in README.md find_tabs_pr.yaml report.log[0m
2022-05-15T12:47:45.8169269Z [36;1mdo[0m
2022-05-15T12:47:45.8169568Z [36;1m  tabs_count=$(grep -P "\t" "${file_name}"|wc -l)[0m
2022-05-15T12:47:45.8169993Z [36;1m  echo "File: ${file_name} changed and content ${tabs_count} of tabs"|tee -a report.log[0m
2022-05-15T12:47:45.8170329Z [36;1mdone[0m
2022-05-15T12:47:45.8224549Z shell: /usr/bin/bash -e {0}
2022-05-15T12:47:45.8224840Z ##[endgroup]
2022-05-15T12:47:45.8383970Z File: README.md changed and content 3 of tabs
2022-05-15T12:47:45.8430911Z File: find_tabs_pr.yaml changed and content 0 of tabs
2022-05-15T12:47:45.8476029Z File: report.log changed and content 0 of tabs
2022-05-15T12:47:45.8511717Z ##[group]Run actions/upload-artifact@v2
2022-05-15T12:47:45.8511977Z with:
2022-05-15T12:47:45.8512192Z   path: report.log
2022-05-15T12:47:45.8512424Z   name: artifact
2022-05-15T12:47:45.8512647Z   if-no-files-found: warn
2022-05-15T12:47:45.8512886Z ##[endgroup]
2022-05-15T12:47:45.9153272Z With the provided path, there will be 1 file uploaded
2022-05-15T12:47:45.9155682Z Starting artifact upload
2022-05-15T12:47:45.9156855Z For more detailed logs during the artifact upload process, enable step-debugging: https://docs.github.com/actions/monitoring-and-troubleshooting-workflows/enabling-debug-logging#enabling-step-debug-logging
2022-05-15T12:47:45.9157909Z Artifact name is valid!
2022-05-15T12:47:45.9929761Z Container for artifact "artifact" successfully created. Starting upload of file(s)
2022-05-15T12:47:46.1156138Z Total size of all the files uploaded is 517 bytes
2022-05-15T12:47:46.1157664Z File upload process has finished. Finalizing the artifact upload
2022-05-15T12:47:46.1463276Z Artifact has been finalized. All files have been successfully uploaded!
2022-05-15T12:47:46.1464528Z 
2022-05-15T12:47:46.1464732Z The raw size of all the files that were specified for upload is 2358 bytes
2022-05-15T12:47:46.1465240Z The size of all the files that were uploaded is 517 bytes. This takes into account any gzip compression used to reduce the upload size, time and storage
2022-05-15T12:47:46.1465560Z 
2022-05-15T12:47:46.1466316Z Note: The size of downloaded zips can differ significantly from the reported size. For more information see: https://github.com/actions/upload-artifact#zipped-artifact-downloads 
2022-05-15T12:47:46.1466709Z 
2022-05-15T12:47:46.1468506Z Artifact artifact has been successfully uploaded!
2022-05-15T12:47:46.1673939Z Post job cleanup.
2022-05-15T12:47:46.1712161Z Post job cleanup.
2022-05-15T12:47:46.2272787Z Post job cleanup.
2022-05-15T12:47:46.3604141Z [command]/usr/bin/git version
2022-05-15T12:47:46.3687898Z git version 2.36.1
2022-05-15T12:47:46.3744774Z Copying '/home/runner/.gitconfig' to '/home/runner/work/_temp/1b3062dc-2c35-41f4-b2f2-8ec813e89152/.gitconfig'
2022-05-15T12:47:46.3759706Z Temporarily overriding HOME='/home/runner/work/_temp/1b3062dc-2c35-41f4-b2f2-8ec813e89152' before making global git config changes
2022-05-15T12:47:46.3763106Z Adding repository directory to the temporary git global config as a safe directory
2022-05-15T12:47:46.3770755Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/04.GitOps/04.GitOps
2022-05-15T12:47:46.3851766Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2022-05-15T12:47:46.3899943Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2022-05-15T12:47:46.4164884Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2022-05-15T12:47:46.4197611Z http.https://github.com/.extraheader
2022-05-15T12:47:46.4214807Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2022-05-15T12:47:46.4253772Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
2022-05-15T12:47:46.4774361Z Cleaning up orphan processes
```	
