# Max Fan
I love to hack, make, and create! 
I'm a senior at Choate Rosemary Hall (a high school) and president of [Choate Programming Union](https://cpu.party), a club that aims to foster a love of programming amongst all students.
I'm also a ham radio operator ([general class](http://www.arrl.org/ham-radio-licenses)) – my callsign is `KC1LTV`. 
I mainly focus on crypto/security related things, although I have a variety of other interests.

As of 2020-12-31, `140/207` of my repositories are public. Here are several of my more interesting recent open-source projects (in no particular order and in varying degrees of completion).

### ➕ Misc
- **[housing-optimization](https://github.com/ChoateProgrammingUnion/housing-optimization)** Optimizing and automating the Choate housing allocation system with Monte Carlo Markov Chains and constraint optimizer techniques with the goal of replacing the current lottery-based system.

- **[geocompose](https://github.com/InnovativeInventor/geocompose)** A library for representing geographical regions as a set of addresses. Intended for use in redistricting.

- **[Choate Zoom Coordinator](https://github.com/ChoateProgrammingUnion/zoom-coordinator):** A unified location for attending classes on Zoom. Currently in production to ~ 1000 people.

- **[mongoset](https://github.com/TadpoleTutoring/mongoset):** An idiomatic, Pythonic way to interact with MongoDB with good defaults. Drop in replacement for the [dataset](https://github.com/pudo/dataset) library.

- **[pbutil](https://github.com/InnovativeInventor/pbutil)** Cross-platform implementation of macOS's pbcopy and pbpaste in Rust. Helps make transitioning from macOS -> Linux easier.

- **[gsimplify](https://github.com/ChoateProgrammingUnion/gsimplify)** A Google Drive to html compiler. Google Drive is ubiquitous for writing and its collaboration and real-time editing features are the best out there. `gsimplify` aims to create a lightweight, more intuitive CMS system powered by Google Drive/docs that compiles a Google drive folder to a fully fledged website. Currently in development for usage in Choate's Student Council website.


### 🔑 Cryptography and Security
- **[dropbox-timestamp](https://github.com/InnovativeInventor/dropbox-timestamp):** Automatic and trustless cryptographic timestamping in Dropbox (with attestations uploaded to Bitcoin) 

- **[pylamport](https://github.com/InnovativeInventor/pylamport):** A python library for generating cryptographic [Lamport](https://en.wikipedia.org/wiki/Lamport_signature) signatures.

- **[homomorphic-encryption](https://github.com/InnovativeInventor/homomorphic-encryption):** Basic homomorphic algebraic operators encrypted with LWE utilizing GPU acceleration and ripple adders. Uses the [NuFHE library](https://github.com/nucypher/nufhe).

- **[Trustless Random Beacon](https://github.com/InnovativeInventor/random-tournament-beacon):** A secure randomness beacon using sequentially applied hashes and hash commitments on the Bitcoin blockchain.
> This was used to generate demonstrably random pairings of a chess tournament to great success! 

- **[monobox](https://github.com/InnovativeInventor/monobox):** A flexible, simple, (and secure) tool for rapidly coding, testing, and deploying applications using Docker.

- **[CTFtools](https://github.com/InnovativeInventor/CTFtools):** Tools for cybersecurity (CTF) competitions. Used by Choate Programming Union's CTF team to win 8th place nationally at picoCTF.

- **[timestamp-api](https://github.com/InnovativeInventor/timestamp-api):** A HTTP api for timestamping via opentimestamps (with attestations on the Bitcoin blockchain).

- **[securechecks](https://github.com/InnovativeInventor/securechecks):** Small security tools and scripts to lock down and prevent pwnage. 

- **[constant-time-benchmark](https://github.com/InnovativeInventor/constant-time-benchmark):** Benchmarking various supposedly constant time algorithms to validate various cryptographic implementations against side-channel attacks in Golang.

### ⚙️ Theory of Computation
- **[pylambda](https://github.com/InnovativeInventor/pylambda):** A Turing complete, experimental prototype programming language based off lambda calculus in Python 

> This project was a weekend project – I plan to revisit this soon and add some types!

- **[lambda-etudes](https://github.com/InnovativeInventor/lambda-etudes)**  Little exercises in lambda calculus to derive and practice my lambda-fu in a typed functional language. Haskell!!! Inspired by the exercises in [Introduction to Lambda Calculus](http://www.cse.chalmers.se/research/group/logic/TypesSS05/Extra/geuvers.pdf) by Henk Barendregt and Erik Barendsen.


### 📖 Machine Learning
- **[chesscompress](https://github.com/InnovativeInventor/chesscompress):** Working towards state-of-the-art chess move compression (~90% compression) with asymmetric numeral systems.

- **[deeppacket](https://github.com/InnovativeInventor/deeppacket):** GAN to fool deep packent inspection (DPI) and circumvent censorship.

- **[TrumpTweets](https://github.com/InnovativeInventor/TrumpTweet):** Machine generated Trump-like tweets.


### 🗄️ Archive Team
I also have spent some time helping out [Archive Team](https://www.archiveteam.org/) by writing software that smartly queues some archiving jobs onto ~100 servers through an IRC interface.

- **[queuebot](https://github.com/InnovativeInventor/queuebot):** A smart autoscaling queueing service for archivebot for eventual upload to the Internet Archive's Wayback Machine (WBM). Currently focusing on automatic archival of missing political and governmental twitter accounts. Live on efnet/#archivebot. 

- **[archivist](https://github.com/InnovativeInventor/archivist):**  Archiving politically and culturally important social media with archiveteam and archivebot (on IRC) to IA's WBM. Currently live on efnet/#archivebot. 

# 🧰 Tooling
*I place a great emphasis on my tooling – my belief is that the more familiar I am with my tools, the better I am equipped to solve the problems I want to solve.*

I usually write code in emacs and spend most of my time on my computer in terminal. My dotfiles (somewhat up to date) are [here](https://github.com/InnovativeInventor/dotfiles). 
I usually use [screen](https://linux.die.net/man/1/screen) over [mosh](https://mosh.org/) to remotely work and develop, but sometimes I use good old-fashioned ssh (using mosh (via Blink) on my school-issued iPad plus a bluetooth keyboard can be very productive!). 
For IRC, I use [WeeChat](https://weechat.org/) with several custom plugins and filters (may be open-sourced soon) and my nick is usually `maxfan8` (you can find me on [efnet](http://www.efnet.org/) and [hackint](https://hackint.org/), although I prefer the latter).

*(Is this latest GitHub feature* **gimmicky**? *Yeah, ^^ it certainly looks like it is!)* Written in emacs ([doom-emacs](https://github.com/hlissner/doom-emacs)).
