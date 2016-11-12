# Awful Git Ideas

What if you track .git using git?

    mkdir bad_idea
    cd bad_idea
    mklink /J .git git
    git add -A
    git commit -m "What the hell am I doing?"
    git add -A
    git commit -m "It only gets worse from here."
    git add -A
    git commit -m "Ok this is enough."