I love to hack, make, and create! 
I'm currently a student at the University of Illinois at Urbana-Champaign.
Formerly, I was president of [Choate Programming Union](https://cpu.party) (my high school CS club).
I'm also a ham radio operator ([general class](http://www.arrl.org/ham-radio-licenses)) – my callsign is `KC1LTV`. 
I'm interested in cryptography/security related things, although I have a variety of other interests.
More recently, I've been doing computational redistricting work at the non-partisan [MGGG redistricting lab](https://mggg.org/).

As of 2020-12-31, `140/207` of my repositories are public. Here are several of my more interesting recent open-source projects (in no particular order and in varying degrees of completion).

### ➕ Misc
- **[node-kayles](https://github.com/InnovativeInventor/node-kayles)** Calculations and generalizations for [Node-Kayles](https://cs.uwaterloo.ca/journals/JIS/VOL23/Wong/wong24.pdf)/[non attacking queens problem](https://www.maa.org/sites/default/files/may_2006_-_noon55524.pdf) in combinatorial game theory. Uses a generalized node-contraction algorithm to achieve improvements over previous calculations in the literature. Written in Rust!

- **[pcompress](https://github.com/InnovativeInventor/pcompress)** Highly efficient compression of districting plans for speeding up gerrymandering research and improving reproducibility. An ergonomic tool meant as a drop-in, faster alternative to standard [GerryChain](https://github.com/mggg/GerryChain) analysis.

- **[geocompose](https://github.com/InnovativeInventor/geocompose)** A library for representing geographical regions as a set of addresses. Intended for use in processing data products for redistricting and calculating precinct stability. Messy code!

- **[housing-optimization](https://github.com/ChoateProgrammingUnion/housing-optimization)** Researching dorm housing allocation systems and optimization techniques with Markov Chain Monte Carlo and constraint optimizer techniques with the goal of replacing the current lottery-based housing allocation system at Choate Rosemary Hall.

- **[Choate Zoom Coordinator](https://github.com/ChoateProgrammingUnion/zoom-coordinator):** A unified location for discovering Zoom links for attending classes on Zoom. [Was in production](http://web.archive.org/web/20200919175321/https://zoom.choate.edu/) to ~ 1000 people at Choate Rosemary Hall.

- **[mongoset](https://github.com/TadpoleTutoring/mongoset):** An idiomatic, Pythonic way to interact with MongoDB with good defaults. Drop in replacement for the Python [dataset](https://github.com/pudo/dataset) SQL library.

- **[pbutil](https://github.com/InnovativeInventor/pbutil)** Cross-platform implementation of macOS's pbcopy and pbpaste in Rust. Helps make transitioning from macOS -> Linux easier.

- **[gsimplify](https://github.com/ChoateProgrammingUnion/gsimplify)** A Google Drive to html compiler. Google Drive is ubiquitous for writing and its collaboration and real-time editing features are the best out there. `gsimplify` aims to create a lightweight, more intuitive CMS system powered by Google Drive/docs that compiles a Google drive folder to a fully fledged website. Currently in development for usage in Choate's Student Council website.


### 🔑 Cryptography and Security
- **[dropbox-timestamp](https://github.com/InnovativeInventor/dropbox-timestamp):** Automatic and trustless cryptographic timestamping in Dropbox (with attestations uploaded to Bitcoin). Merkle trees rock! 

- **[pylamport](https://github.com/InnovativeInventor/pylamport):** A Python library for generating cryptographic [Lamport](https://en.wikipedia.org/wiki/Lamport_signature) signatures.

- **[homomorphic-encryption](https://github.com/InnovativeInventor/homomorphic-encryption):** Basic homomorphic algebraic operators encrypted with LWE utilizing GPU acceleration and ripple adders. Uses the [NuFHE library](https://github.com/nucypher/nufhe).

- **[Trustless Random Beacon](https://github.com/InnovativeInventor/random-tournament-beacon):** A secure randomness beacon using sequentially applied hashes and hash commitments on the Bitcoin blockchain.
> This was used to generate demonstrably random pairings of a chess tournament to great success! 

- **[monobox](https://github.com/InnovativeInventor/monobox):** A flexible, simple, (and secure) tool for rapidly coding, testing, and deploying applications using Docker. Currently deprecated.

- **[CTFtools](https://github.com/InnovativeInventor/CTFtools):** Tools for cybersecurity (CTF) competitions. Used by Choate Programming Union's CTF team to win 8th place nationally at picoCTF.

- **[timestamp-api](https://github.com/InnovativeInventor/timestamp-api):** A HTTP api for timestamping via opentimestamps (with attestations on the Bitcoin blockchain).

### ⚙️ Theory of Computation
- **[pylambda](https://github.com/InnovativeInventor/pylambda):** A lambda calculus implementation in Python.

> This project was a weekend project – I plan to revisit this soon and add some types!

- **[lambda-etudes](https://github.com/InnovativeInventor/lambda-etudes)**  Little exercises in lambda calculus to derive and practice my lambda-fu in a typed functional language. Haskell!!! Inspired by the exercises in [Introduction to Lambda Calculus](http://www.cse.chalmers.se/research/group/logic/TypesSS05/Extra/geuvers.pdf) by Henk Barendregt and Erik Barendsen.


### 📖 Machine Learning
- **[chesscompress](https://github.com/InnovativeInventor/chesscompress):** Chess move compression for efficient storage of chess games (~90% compression) with asymmetric numeral systems.

- **[deeppacket](https://github.com/InnovativeInventor/deeppacket):** GAN to fool deep packent inspection (DPI) and circumvent censorship.


### 🗄️ Archive Team
I also have spent some time helping out [Archive Team](https://www.archiveteam.org/) by writing software that smartly queues some archiving jobs onto ~100 servers through an IRC interface.

- **[queuebot](https://github.com/InnovativeInventor/queuebot):** An autoscaling queueing service for archivebot for eventual upload to the Internet Archive's Wayback Machine (WBM). Currently focusing on automatic archival of missing political and governmental twitter accounts. Was live on efnet/#archivebot. Messy code!

- **[archivist](https://github.com/InnovativeInventor/archivist):**  Archiving politically and culturally important social media with archiveteam and archivebot (on IRC) to IA's WBM. Was live on efnet/#archivebot. Messy code!


# 🧰 Tooling
I usually write code in emacs and spend most of my time on my computer in terminal (alacritty). My dotfiles (somewhat up to date) are [here](https://github.com/InnovativeInventor/dotfiles). 
I usually use tmux over [mosh](https://mosh.org/) to remotely work and develop, but sometimes I use good old-fashioned ssh (using mosh (via Blink) on my school-issued iPad plus a bluetooth keyboard can be very productive!). 
For IRC, I use [WeeChat](https://weechat.org/) with several custom plugins and filters (may be open-sourced in the future) and my nick is usually `maxfan8` (you can find me on [efnet](http://www.efnet.org/) and [hackint](https://hackint.org/), although I prefer the latter).

Written in ([doom emacs](https://github.com/hlissner/doom-emacs)).
