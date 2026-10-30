# Engineering-portfolio
Engineering project documentation and portfolio

* Note: GitHub does NOT organize folder by creation date, if you wish to see folders by date run the following code snipet in your terminal.
# One-liner
WIDTH=35 ; for filename in * ; do created_date=$(git log --follow --format=%ad --date default $filename | tail -1); printf "%-${WIDTH}s |      %s \n" "$created_date" $filename ; done | sort


# More readable multi-line

WIDTH=35        # Column padding width
DIR=.           # You can substitute this for a directory name
for filename in "${DIR}"/*
do 
  created_date="$(git log --follow --format=%ad --date default $filename | tail -1)"
  printf "%-${WIDTH}s |      %s \n" "$created_date" $filename
done | sort
