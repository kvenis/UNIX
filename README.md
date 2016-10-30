# UNIX
#sort from the middle of a file
# usage: bash scripts.sh file name end_line num_lines
head -n "$2" "$1" |tail -n "$3"
