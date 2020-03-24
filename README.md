# outerlook

not for interviews, look elsewhere!

## FW

### C

1. `fw/c/bit_insert` :: Jim :: Bit insertion helper stuff
1. `fw/c/bitstring` :: Jim :: bitstring test
1. `fw/c/setbit` :: Jim :: bit set test
1. `fw/c/ll` :: Shaba :: Linked list -> queue -> stack
1. `fw/c/pt` :: Brett :: pthread sequence printer

## SW

### C++

1. `sw/c/matrix` :: Shaba :: Matrix<T, N, M> and associated methods

### Python

1. `sw/py/wc` :: Shaba :: word count program
2. `sw/py/subs` :: Shaba :: random regular expression tester / playground

## Cloning for Interviews

1. Create a completely empty public repository (for the repository name, pick the GitHub suggested random name and prepend interview- in front of it): https://github.com/organizations/recogni/repositories/new
2. Clone the original outerlook questions repository: `git clone git@github.com:recogni/outerlook`
3. Go into the outerlook repository: `cd outerlook`
4. Update its remote to the newly-created empty repository: `git remote set-url origin git@github.com:recogni/interview-fluffy-train.git`
5. Reset it to the very first commit to strip history: `git reset --soft $(git rev-list --max-parents=0 HEAD)`
6. Run any shell commands (e.g. rm -rf sw, etc.) to trim or add contents and get it into the exact state you want
7. Commit everything and push: `git add . && git commit --amend --no-edit && git push`
