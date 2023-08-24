This is a detached fork of lemmy server. Not to be confused with lemmy-ui or other front-end applications.

This project is experimental.

It is starting with the Lemmy server Rust codebase. Thank you to the Lemmy project.

## Expectations

1. No claims are made to be able to replace Reddit or other traditioanl sites. Features are lacking and there are known performance problems with the SQL in the code.
2. There are known bugs realted to data integrity and consistency sharing data with peer servers.
3. The intention is to run a public forum with public content, public messages and comments. Data is shared over ActivePub federation with over 1000 other Lemmy servers and even non-Lemmy servers in the network.
4. Experimental may me broken code just for the sake of trying out new features or addressing some crash or design issue.
5. Nobody has hired or funded this project at start, it's just contribuiton of free labor currently, and please understand that it is encourged to seek out alternates as you wish. Part of being on the ActivePub federated network is to have choices.
6. If you run this code or use parts of it, assume data integrity and other problems are in the code base. Typically this is intended to be run by small-time oeprators on a low-budget hosting solution. It was specifcally created during a period of transition away from big corporate media providers, think small-time tavern owner/operaor.

The [Wiki on GitHub](https://github.com/MusicSongs-Org/MusicSongs.org_Lemmy/wiki) has more about why this fork and the new website was created on August 24, 2023.

Thank you and may all men have a better future.

# Docker, Install, etc

Docker or other install scripts are outside the scope of the project, part of eperimental is to try and break free to do things more 'from sratch' install as Lemmy project calls it.

It is generally advised to run with PostgreSQL 15.4 or PostgreSQL 16. Compiling the Rust app from scratch is pretty much recommended and gets around need to have Docker builds for ARM and others, as expereince shows that Lemmy's Rust code compiles fine on ARM servers.

Technical notes and requests for help from other experimeters - there is a forum on Github and there will be a community on MusicSongs.org Lemmy. It's encouraged that you not try to use private messaging or private communiations to discuss the project. The intention is to leave problems in the open and not make any effort to keep technical problems or discussions hugh-hush, back-stage or behind the scenes. Experimental is the word ;)

Thep project does not provide support or make claims to do so... the goal is to try and highlight where compatibility with Lemmy server's main code might be broken and go from there.

Thank you.
