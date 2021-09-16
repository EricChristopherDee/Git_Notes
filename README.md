Commands:

    git status shows untracked files (the method used to determine file status/color in text editors)
    
    git log / git log --oneline shows commits and heads

    git reset HEAD filename sets the head reference back to the original commit if it has been changed (unstages changes)

    git checkout HEAD file name movement between heads

    git checkout -- filename discards changes and resets to current commit

    git fetch checks metadata/current repo state

    git clean -d -f removes all tracked files, helpful to merge an uncooperative origin... just make sure to commit them first