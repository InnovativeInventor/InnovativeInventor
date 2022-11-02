I love to hack, make, and create! 
I'm currently a student at the University of Illinois at Urbana-Champaign (UIUC).
I'm also a ham radio operator ([general class](http://www.arrl.org/ham-radio-licenses)) – my callsign is `KC1LTV`. 
I have a wide variety of interests.
More recently, I've been doing computational redistricting work at the non-partisan [MGGG redistricting lab](https://mggg.org/).

Here are several of my more interesting recent projects (in no particular order and in varying degrees of completion).

### ➕ Misc
- **[node-kayles](https://github.com/InnovativeInventor/node-kayles)** Calculations and generalizations for [Node-Kayles](https://cs.uwaterloo.ca/journals/JIS/VOL23/Wong/wong24.pdf)/[non attacking queens problem](https://www.maa.org/sites/default/files/may_2006_-_noon55524.pdf) in combinatorial game theory. Uses a generalized node-contraction algorithm to achieve improvements over previous calculations in the literature. Written in Rust!

- **[pcompress](https://github.com/InnovativeInventor/pcompress)** Highly efficient compression of districting plans for speeding up gerrymandering research and improving reproducibility. An ergonomic tool meant as a drop-in, faster alternative to standard [GerryChain](https://github.com/mggg/GerryChain) analysis. Currently the main method of running and analyzing experiments at the [MGGG redistricting lab](https://mggg.org/).

- **[geocompose](https://github.com/InnovativeInventor/geocompose)** A library for representing geographical regions as a set of addresses. Intended for use in processing data products for redistricting and calculating precinct stability. Messy code!

- **[housing-optimization](https://github.com/ChoateProgrammingUnion/housing-optimization)** Examining dorm housing allocation systems and optimization techniques with Markov Chain Monte Carlo and constraint optimizer techniques with the goal of replacing the current lottery-based housing allocation system at Choate Rosemary Hall. Achieved a 15% decrease in the number of students who didn't get their first choice when simulated on *real historical data*.

- **[Choate Zoom Coordinator](https://github.com/ChoateProgrammingUnion/zoom-coordinator):** A unified location for discovering Zoom links for attending classes on Zoom. [Was in production](http://web.archive.org/web/20200919175321/https://zoom.choate.edu/) to ~ 1000 people at Choate Rosemary Hall. Messy code!

- **[mongoset](https://github.com/TadpoleTutoring/mongoset):** A Pythonic ORM library to interact with MongoDB with good defaults. Drop-in replacement for the Python [dataset](https://github.com/pudo/dataset) SQL library. Check out the docs [here](http://mongoset.max.fan).

- **[pbutil](https://github.com/InnovativeInventor/pbutil)** Cross-platform implementation of macOS's pbcopy and pbpaste in Rust. Helps make transitioning from macOS -> Linux easier.


### 🔑 Cryptography and Security
- **[dropbox-timestamp](https://github.com/InnovativeInventor/dropbox-timestamp):** Automatic and trustless cryptographic timestamping in Dropbox (with attestations uploaded to Bitcoin). Merkle trees rock! 

- **[pylamport](https://github.com/InnovativeInventor/pylamport):** A Python library for generating cryptographic [Lamport](https://en.wikipedia.org/wiki/Lamport_signature) signatures.

- **[homomorphic-encryption](https://github.com/InnovativeInventor/homomorphic-encryption):** Basic homomorphic algebraic operators encrypted with LWE utilizing GPU acceleration and ripple adders. Uses the [NuFHE library](https://github.com/nucypher/nufhe).

- **[Trustless Random Beacon](https://github.com/InnovativeInventor/random-tournament-beacon):** A secure randomness beacon using cryptographic commitments on the Bitcoin blockchain and sequentially applied hashes (as time locks). Can be used to generate "nothing up my sleeve" seeds.
> This was used to generate demonstrably random pairings for a chess tournament I was running to great success! 

- **[CTFtools](https://github.com/InnovativeInventor/CTFtools):** Tools for cybersecurity (CTF) competitions. Used by Choate Programming Union's CTF team to win 8th place nationally at picoCTF.

### ⚙️ Logic and Computation
- **[hack-python-types](https://github.com/InnovativeInventor/hack-python-types):** Hacking Python’s type-checker to construct a propositional, constructive logic theorem prover via the Curry-Howard correspondence and the BHK interpretation of intuitionistic logic. ([see blog post](https://max.fan/posts/hacking-python-types/)) 

- **[lambda-etudes](https://github.com/InnovativeInventor/lambda-etudes)**  Little exercises in lambda calculus to derive and practice my lambda-fu in a typed functional language. Haskell!!! Inspired by the exercises in [Introduction to Lambda Calculus](http://www.cse.chalmers.se/research/group/logic/TypesSS05/Extra/geuvers.pdf) by Henk Barendregt and Erik Barendsen.

- **[tree-logics](https://github.com/InnovativeInventor/tree-logics)** Formally verified, shallow embeddings of various tree logics, in Coq, along with some consistency, completness, and soundness proofs.

- **[turing-impl](https://github.com/InnovativeInventor/turing-impl)** A simple Turing machine implementation.

### 📖 Machine Learning
- **[chesscompress](https://github.com/InnovativeInventor/chesscompress):** Chess move compression for efficient storage of chess games (~90% compression) with asymmetric numeral systems.

- **[deeppacket](https://github.com/InnovativeInventor/deeppacket):** GAN to fool deep packent inspection (DPI) and circumvent censorship.


# 🧰 Tooling
I usually write code in emacs and spend most of my time on my computer in terminal (alacritty). My dotfiles (somewhat up to date) are [here](https://github.com/InnovativeInventor/dotfiles). 
I usually use tmux over [mosh](https://mosh.org/) to remotely work and develop, but sometimes I use good old-fashioned ssh. 
For IRC, I use [WeeChat](https://weechat.org/) with several custom plugins and filters (may be open-sourced in the future) and my nick is usually `maxfan8` (you can find me on [efnet](http://www.efnet.org/) and [hackint](https://hackint.org/), although I prefer the latter).
