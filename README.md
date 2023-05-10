# changelog

The iTrackBites changelog is where I will be quickly documenting more of the technical side of new releases from sprints and releases. This will not replace blogs and other marketing/PR, but will help us all keep track of ongoing changes. It will be public facing.

## Creating a post
We use Jekyll (jekyllrb.com) as the platform for our changelog blog. It’s a blogging platform that doesn’t require any databases and is just a ruby script that more or less creates static blog pages. It’s free and looks pretty good.

This is Jekyll’s documentation on how to create a post:
[Posts | Jekyll • Simple, blog-aware, static sites](https://jekyllrb.com/docs/posts/)

Here are steps for doing so in our changelog

1. Goto the [Development Board](https://github.com/orgs/sunshinehealthstudios/projects/15)
2. Filter by the release you're creating a new post.
3. Use the issues listed to create a new changelog file in the next steps
5. Create a new file in our GitHub `changelog` repository in the `_posts` directory [direct link](https://github.com/sunshinehealthstudios/changelog/new/main/_posts) or you can navigate to the directory and then tap `Add file` and `Create new file`
![](Screen%20Shot%202021-06-18%20at%202.56.58%20PM.png)
6. Name the file with the right format of `YEAR-MONTH-DAY-title.md` using the `-` in place of a space ` `. 
Example: `2021-06-12-how-to-write-a-blog.md`
7. Add the contents of the GitHub Issues to this new markdown file. Remember to only include public facing issues and adjust titles as needed.
8. Change the `title` from the version number to something meaningful. Best to keep it consistent with the file name.
9. Type in an `Overview` that sums this all up. This may or may not be used by Apple Store “what’s new” section or Google Play’s similar section. Send this to Andrew and Oscar so that they can use it to update if needed.
10. Remove any internal items that the public just doesn’t need to know about, specifically anything that’s sensitive.
11. You can edit any language, grammar, etc. with each of the items as well.
12. I normally prepend  `Fixed: `  to any issue that was fixed
13. Then you want to commit the new file, which is done at the bottom of this GitHub screen you’re on.
14. Give a good name of what you’re doing, such as `Updating changelog with v7.4 release` — you can leave the description blank
15. Make sure you are committing directly to the `main` branch and tap `Commit new file`
16. After awhile, GitHub will run the Jekyll code to publish your blog. Check `https://changelog.itrackbites.com` when it’s ready. You’ll know when it’s ready when there’s a message in #technical_dribble on slack saying it's done.
