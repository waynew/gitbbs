# gitbbs

## What Is GitBBS?

Are you sick of modern social media? Do push notifications and infinite scroll
get you down? Do you long for the simpler days, when the web was young, and you
chose when to interact with the Internet?

if so, gitbbs is for you!

GitBBS is an idea built on a tool that makes communication more of a choice.
The way it works is that you use your text editor to interact with posts, and
git to share your posts with others. That means that you can use the Internet,
sneakernet, or even git over Avian Protocol.

## How To

You're convinced and you'd like to use gitbbs? Cool! Well, you're gonna want to
clone this repo, or any of its forks. The default one should be available here:

    git clone https://github.com/waynew/gitbbs.git

Once you've got the repo cloned, simply head to the topics folder. Here is
where you'll find topics that you can interact with. To create a new topic,
simply create a new folder. To create a new discussion in the topic, create a
new file with a name `YYYYMMDD-this-is-my-topic.txt`.

Entries in the topic basically look like plaintext email headers. The two
required fields are From and Date (which can include time+timezone information)

When you finish composing/replying to topics, simply make a commit and then
either push your changes or create a pull request.

## Registering Your Fork

If you have a public fork available, drop a link to it in the `forks.txt` file.
This will allow other users to add your copy of the repo, which then can be
retrieved with `git fetch --all`.


## Conventions

Be kind. There may be parts of the BBS for more iintense discussions, but
default to kindness.

Text should be wrapped at roughly 80 columns. Not a hard limit, but, preferred.

Don't edit other people's responses, unless it's some kind of awful (hate
speech, racism, etc. etc.). If you have to, replace it with:

    <edited out from GIT_HASH>

where `GIT_HASH` is found with `git rev-parse HEAD`. This is git, so nothing is
easily forgotten.

For discussion about gitbbs itself, see the meta topic. The `utils` folder
contains scripts that you might find useful/helpful.

Anonymity is probably not truly possible. If you want some measure of identity,
look into gpg signing of commits.

Don't commit binary files.
