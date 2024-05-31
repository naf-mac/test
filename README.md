# test
find . -type f -exec sed -i 's/safeway/flofam/g' {} +
grep -Hrn safeway * | wc -l
