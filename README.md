# Comparing Hashes

<h2>Objective</h2>

Investigate and compare two files to verify if they are identical.

<h2>Tasks</h2>

- Check the contents of each file.
- Generate a hash for each file and compare the hashes.
- Determine whether the files are identical or not.

<h2>Steps Taken</h2>

- Used `ls` command to list and identify the two files I will be investigating.
- Read the contexts of `file1.txt` and `file2.txt` using the `cat` command.

Upon first look, the contents of these files seem identical. To further verify, we will generate a hash for each file using `sha256sum`.

![1](https://github.com/DigitalWatchmen/Hashes/assets/164795269/f40898c7-7c46-4333-b33a-6f342f3f0fb5)

- Generated a hash for `file1.txt` and `file2.txt` using `sha256sum`.
- Created two new files to contain corresponding hashes for `file1.txt` and `file2.txt` using `sha256sum`.

With the two hashes generated, we can be determine that although the contains looked identical, there are differences between the two files. 

![2](https://github.com/DigitalWatchmen/Hashes/assets/164795269/4123ad8c-9f9e-45a0-90a9-21df4e269c01)

- Compared the two files created `file1hash` and `file2hash` using the `cmp` command.

The output shows us what and where the differences are found between the two file hashes.

![3](https://github.com/DigitalWatchmen/Hashes/assets/164795269/b9b1b67a-439e-4398-9af4-5ceca403b81d)

<h2>Conclusion</h2>

`file1.txt` and `file2.txt` are not identical files.
