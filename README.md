- 👋 Hi, I’m @KRClark49
- 👀 I’m interested in ...  Voice Dictation via Nerd-Dictation
- 🌱 I’m currently learning ... Installing Nerd-Dictation  on my Linux Mint-22 system.
- 💞️ I’m looking to collaborate on ... Finding my mis-steps on installation.
- 📫 How to reach me ...  clarknws@united.net
- 😄 Pronouns: ...
- ⚡ Fun fact: ...  Not Linux expert. However have used Linux for 3 years and fairly conversant with terminal and file hierarchy.

<!---
KRClark49/KRClark49 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
 I apologize for the length, but I wanted to provide an accurate picture of files etc used in the installation.

 Greetings  nerd-dictation experts. 
I am not a nerd, but I've been using Linux for 3 years.
I'm currently running Linux-Mint-22.
After days of trying to implement nerd-dictation on my
system, I just can't get nerd-dictation to execute.

When I bring up a blank text-file, then press the ALT-B key
which is bound to the command "nerd-dictation-begin.sh" file,
I get no audible response when I speak "testing one two three'.

My microphone headset works ok as I hear youtube videos fine.

Below is a tree list of all the components on my system.

kenneth@kenneth-Inspiron-3470:~$ sudo locate nerd-dictation
[sudo] password for kenneth:           
/home/kenneth/nerd-dictation
/home/kenneth/.config/nerd-dictation
/home/kenneth/.config/nerd-dictation/model
/home/kenneth/.config/nerd-dictation/model/README
/home/kenneth/.config/nerd-dictation/model/am
/home/kenneth/.config/nerd-dictation/model/conf
/home/kenneth/.config/nerd-dictation/model/graph
/home/kenneth/.config/nerd-dictation/model/ivector
/home/kenneth/.config/nerd-dictation/model/am/final.mdl
/home/kenneth/.config/nerd-dictation/model/conf/mfcc.conf
/home/kenneth/.config/nerd-dictation/model/conf/model.conf
/home/kenneth/.config/nerd-dictation/model/graph/Gr.fst
/home/kenneth/.config/nerd-dictation/model/graph/HCLr.fst
/home/kenneth/.config/nerd-dictation/model/graph/disambig_tid.int
/home/kenneth/.config/nerd-dictation/model/graph/phones
/home/kenneth/.config/nerd-dictation/model/graph/phones/word_boundary.int
/home/kenneth/.config/nerd-dictation/model/ivector/final.dubm
/home/kenneth/.config/nerd-dictation/model/ivector/final.ie
/home/kenneth/.config/nerd-dictation/model/ivector/final.mat
/home/kenneth/.config/nerd-dictation/model/ivector/global_cmvn.stats
/home/kenneth/.config/nerd-dictation/model/ivector/online_cmvn.conf
/home/kenneth/.config/nerd-dictation/model/ivector/splice.conf
/home/kenneth/nerd-dictation/.editorconfig
/home/kenneth/nerd-dictation/.git
/home/kenneth/nerd-dictation/.gitignore
/home/kenneth/nerd-dictation/LICENSE
/home/kenneth/nerd-dictation/_misc
/home/kenneth/nerd-dictation/changelog.rst
/home/kenneth/nerd-dictation/examples
/home/kenneth/nerd-dictation/hacking.rst
/home/kenneth/nerd-dictation/nerd-dictation
/home/kenneth/nerd-dictation/nerd-dictation-cookie
/home/kenneth/nerd-dictation/package
/home/kenneth/nerd-dictation/pyproject.toml
/home/kenneth/nerd-dictation/readme-sox.rst
/home/kenneth/nerd-dictation/readme-ydotool.rst
/home/kenneth/nerd-dictation/readme.rst
/home/kenneth/nerd-dictation/scripts
/home/kenneth/nerd-dictation/tests
/home/kenneth/nerd-dictation/vosk-model-small-en-us-0.15.zip
/home/kenneth/nerd-dictation/.git/HEAD
/home/kenneth/nerd-dictation/.git/branches
/home/kenneth/nerd-dictation/.git/config
/home/kenneth/nerd-dictation/.git/description
/home/kenneth/nerd-dictation/.git/hooks
/home/kenneth/nerd-dictation/.git/index
/home/kenneth/nerd-dictation/.git/info
/home/kenneth/nerd-dictation/.git/logs
/home/kenneth/nerd-dictation/.git/objects
/home/kenneth/nerd-dictation/.git/packed-refs
/home/kenneth/nerd-dictation/.git/refs
/home/kenneth/nerd-dictation/.git/hooks/applypatch-msg.sample
/home/kenneth/nerd-dictation/.git/hooks/commit-msg.sample
/home/kenneth/nerd-dictation/.git/hooks/fsmonitor-watchman.sample
/home/kenneth/nerd-dictation/.git/hooks/post-update.sample
/home/kenneth/nerd-dictation/.git/hooks/pre-applypatch.sample
/home/kenneth/nerd-dictation/.git/hooks/pre-commit.sample
/home/kenneth/nerd-dictation/.git/hooks/pre-merge-commit.sample
/home/kenneth/nerd-dictation/.git/hooks/pre-push.sample
/home/kenneth/nerd-dictation/.git/hooks/pre-rebase.sample
/home/kenneth/nerd-dictation/.git/hooks/pre-receive.sample
/home/kenneth/nerd-dictation/.git/hooks/prepare-commit-msg.sample
/home/kenneth/nerd-dictation/.git/hooks/push-to-checkout.sample
/home/kenneth/nerd-dictation/.git/hooks/sendemail-validate.sample
/home/kenneth/nerd-dictation/.git/hooks/update.sample
/home/kenneth/nerd-dictation/.git/info/exclude
/home/kenneth/nerd-dictation/.git/logs/HEAD
/home/kenneth/nerd-dictation/.git/logs/refs
/home/kenneth/nerd-dictation/.git/logs/refs/heads
/home/kenneth/nerd-dictation/.git/logs/refs/remotes
/home/kenneth/nerd-dictation/.git/logs/refs/heads/main
/home/kenneth/nerd-dictation/.git/logs/refs/remotes/origin
/home/kenneth/nerd-dictation/.git/logs/refs/remotes/origin/HEAD
/home/kenneth/nerd-dictation/.git/objects/info
/home/kenneth/nerd-dictation/.git/objects/pack
/home/kenneth/nerd-dictation/.git/objects/pack/pack-43bc45ef000dfd05fd30ddd60bd767146b489dff.idx
/home/kenneth/nerd-dictation/.git/objects/pack/pack-43bc45ef000dfd05fd30ddd60bd767146b489dff.pack
/home/kenneth/nerd-dictation/.git/objects/pack/pack-43bc45ef000dfd05fd30ddd60bd767146b489dff.rev
/home/kenneth/nerd-dictation/.git/refs/heads
/home/kenneth/nerd-dictation/.git/refs/remotes
/home/kenneth/nerd-dictation/.git/refs/tags
/home/kenneth/nerd-dictation/.git/refs/heads/main
/home/kenneth/nerd-dictation/.git/refs/remotes/origin
/home/kenneth/nerd-dictation/.git/refs/remotes/origin/HEAD
/home/kenneth/nerd-dictation/_misc/readme_update_helptext.py
/home/kenneth/nerd-dictation/examples/begin_end_commands
/home/kenneth/nerd-dictation/examples/default
/home/kenneth/nerd-dictation/examples/language_tool_auto_grammar
/home/kenneth/nerd-dictation/examples/vosk_grammar
/home/kenneth/nerd-dictation/examples/begin_end_commands/nerd-dictation.py
/home/kenneth/nerd-dictation/examples/default/nerd-dictation.py
/home/kenneth/nerd-dictation/examples/language_tool_auto_grammar/nerd-dictation.py
/home/kenneth/nerd-dictation/examples/vosk_grammar/nerd-dictation.py
/home/kenneth/nerd-dictation/examples/vosk_grammar/vosk-grammar.json
/home/kenneth/nerd-dictation/package/guix
/home/kenneth/nerd-dictation/package/python
/home/kenneth/nerd-dictation/package/readme.rst
/home/kenneth/nerd-dictation/package/guix/readme.rst
/home/kenneth/nerd-dictation/package/python/readme.rst
/home/kenneth/nerd-dictation/package/python/setup.py
/home/kenneth/nerd-dictation/scripts/nerd-dictation-begin.sh
/home/kenneth/nerd-dictation/scripts/nerd-dictation-end.sh
/home/kenneth/nerd-dictation/tests/from_words_to_digits.py

Additional files NOT in the "/home/kenneth/nerd-dictation" directory and subdirectories.

/home/kenneth/.bashrc
At the bottom of the above file I added two statements;
export PATH=$PATH:'~/.config/nerd-dictation/nerd-dictation.py'
export PATH=$PATH:'~/.config/nerd-dictation/model'

Root:  (admin:///root).bashrc
At the bottom of the above file I added two statements;
export PATH=$PATH:'~/.config/nerd-dictation/nerd-dictation.py'
export PATH=$PATH:'~/.config/nerd-dictation/model'

Contents of the file: /home/kenneth/nerd-dictation/scripts/nerd-dictation-begin.sh

#!/bin/bash
sudo ./nerd-dictation begin --vosk-model-dir ./mod  --cookie ./home/kenneth/nerd-dictation/nerd-dictation-cookie  --vosk-grammar-file ./home/kenneth/nerd-dictation/examples/vosk-grammar --timeout 15 --simulate-input-tool 'YDOTOOL' & 

Contents of the file: /home/kenneth/nerd-dictation/scripts/nerd-dictation-end.sh

#!/bin/bash
sudo ./nerd-dictation end -h --cookie ./home/kenneth/nerd-dictation/scripts/nerd-dictation-cookie & 

Command Issued on binding Keyboard Shortcut:  ALT-B

python3  /home/kenneth/nerd-dictation/scripts/nerd-dictation-begin.sh

Command Issued on binding Keyboard Shortcut:  ALT-C

python3  /home/kenneth/nerd-dictation/scripts/nerd-dictation-end.sh

I executed sudo rm /usr/lib/python3.*/EXTERNALLY-MANAGED , to remove this file
as recommended in the forum.

I am running ydotoold daemon in background.

I will be eternally greatful for any help provided.

Kenneth Clark
931-619-2149




