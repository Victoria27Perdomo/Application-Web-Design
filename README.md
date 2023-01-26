## Activity 1

***

### Data

**1. Name:** Victoria Chiquinquirá Perdomo Bravo

**2. Registration number:** 2959023

**3. Degree:** Software Engineer

**4. Semester:** 6th semester

***

### Subject data

**1. Name:** Web Application Design

**2. Professor's name:** Luis Romeo Manzur Gómez

***

### What is Markdown used for

Markdown is a markup language used mainly for documentation on repositories like GitHub or GitLab; it's main purpose its to allow users to add formatting elements to plain text without
the need to use a a text editor or HTML tags, for example, instead of using an HTML tag like "h1" for a heading, we can use a hash symbol instead, allowing us to implement the same 
functions with more simplicity, making it useful due to the nature of documentation files, which more often than not tends to be quite extensive, making the Markdown language far more 
practical to use.

***

## Homework 1

***

### Markdown tagging options

---

#### Heading

Use \# for creating a heading, the number of \# will impact the size:

\# Size 1 (Maximum size)

\## Size 2

\### Size 3

\#### Size 4

\##### Size 5

\###### Size 5 (Minimum size)

---

#### Quote and copyright

Use \> for creating a quote and the &copy method for copyright symbol.

> This is a quote

&copy; This is a copyright symbol

---

#### Hyperlink

To add a hyperlink we type the name inside square brackets [] and the link inside round brackets ():

\[Name](Link "Name")

[YouTube](https://www.youtube.com/ "YouTube")

---

#### Image file

To add an image file we follow a method similar to the hyperlink, but we just add an exclamation mark ! before the square brackets []:

\![Name](Link)

![SylveonGIF](https://tenor.com/bB7gl.gif)

---

#### Code

\To add a line of code we use backquotes \`\`:

\`int N;`

`int N;`

---

#### Code blocks

To add a block of multiple lines of code we use 3 backquotes before and after:

\```

void (main) {

	int N = 0;

	int N1 = N + 1;

}

\```

```
void (main) {
	int N = 0;
	int N1 = N + 1;
}
```

---

#### Table

To create a table we must follow the next structure:

\|Heading |Heading |Heading |

\|--      |--      |--      |

\|Info    |Info    |Info    |

We must consider that the dash - symbolizes the number of characters allowed, for example 2 dashes \-- means that the column size cannot go over 2 characters 
(this does not affect the heading).

|Name   |Age |Career |
|-------|--  |---    |
|Vicky  |20  |IDS    |

---

#### List

To create a list we must simply use numbers and symbols, for example:

\1. Item

\2. Item

\	* Sub-item

\* Unordered item

1. One
2. Two
	* 2.1
* 10

---

#### Taglist

To create a taglist we must use both dashes and square brackets, the dash - must go before the square brackets [], for example:

\-[] Hello

-[] Hello

-[x] Hi

---

#### Lines

To create lines we must simply add 3 dashes \--- or asterisks \***, for example:

This line was created with 3 dashes

---

This line was created with 3 asterisks

***

---

### GIT commands

***

#### Status

We use the following command when we want to check the status of our local repository:

	git status

***

#### Adding files

When we want to add a new file individually to our repository we use the following command:

	git add [file-name.txt]

But when we want to add all files we use the next command:

	git add -A

***

#### Commit comments

When we do a commit we can include a comment to indicate the purpose of the commit, like a change made, a new file, etc., we use the following command:

	git commit -m "[commit message]"

***

#### Upload changes

To upload changes made to the repository we use the push command, however it is worth mentioning that there a different push commands based on the type of operation we want to do, but 
the command for uploading changes mainly is:

	git push

***

#### Create, browse and delete branches

To manipulate branches we use the branch command, and just like the push command, there a different branch commands that serve a different purpose:

To create a branch we use:

	git branch [branch name]

To search a branch we use:

	git branch

To delete a branch we use:

	git branch -d [branch name]

***

#### Rolling back

Rolling back means we want to go back to a commit done before, it can also be considered as undoing an action or going back to a certain point in our operations, to do this we use the 
following command:

	git reset commithash (commithash is the first 7 characters of the commit we can find in the log)

***

### END