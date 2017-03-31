Here's a fun project to create a collaborative story.

Setup
-----
Run the following commands

    cd ~;
    git clone https://github.com/cdosborn/story.git;
    cd ~/story;


Stage 1
-------
1.1) Add at least one file to the sentences directory, it should only have a
single line. Look at the file `sentences/once-upon-a-time.txt` as an
example.

1.2) Commit your changes (remember to add them to the stage first)

1.3) Push your changes

1.4) Run `git pull` (and wait for other people's sentences to arrive)

Stage 2
-------
We are now going to form a story from these sentences. To see a sample story
look at the file `stories/a-sample-story.txt`.  A story is going to be a list
of file names from our sentences directory.

2.1) Create your own story like the sample story.

2.2) To output your entire story you're going to run the following command.

    cat $(cat stories/<NAME OF YOUR STORY FILE>)

2.3) After it looks good, add your story to the repo and push it up to github

Stage 3
-------
Without changing our story files, we're going to make changes to the sentences
(which will in turn change the stories). Update two different sentence files
(sentences you did not create).  Maybe take an existing sentence file and add
another sentence to it (maybe along the same train of thought or not :P).

3.1) Commit the two sentence files you changed (change someone else's
sentences). Push your changes up, and pull other's changes down as well.

3.2) Rerun the command from 2.2 and see if your story is different now (or
funny?).


