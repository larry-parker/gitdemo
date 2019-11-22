Learned:
echo "Apple Pie" | git object-hash --stdin, creates hash of contents "Apple Pie"
echo "Apple Pie" | git object-hash --stdin -w , creates blob with contents "Apple Pie"

git cat-file <hash> -t, shows type
git cat-file <hash> -p, shows contents of hash

git count-objects , counts number of objects in object database

curl -u '<username>' https://api.github.com/user/repos -d '{"name":"<reponame>"}'
git add origin https://github.com/<username>/<reponame>
git push -u origin master
