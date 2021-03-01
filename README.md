# Jekyll Resume Template + Manager
*A modern-looking resume template & manager built with Jekyll, that can be hosted on GitHub Pages.*

Do you spend a lot of time writing resumes, copying contents from one resume to another?

Do you wish you could just fill in your info once, and select which entries to include in your current resume?

Do you want one place to see and manage all of your resumes?

This template is for you!

Easily build and manage several custom-tailored resumes from a single dataset, automate the boring stuff so that you can quickly apply for new openings as soon as they open.
(And they look cool, too 👌).

## Prerequisites
1. Some basic understanding of Jekyll and Bundler
2. Some experience with HTML and Markup (YAML)

## Running locally
To test locally, run the following in your terminal:

1. Clone repo locally
1. `bundle install`
2. `bundle exec jekyll serve`
3. Open your browser to `localhost:4000`

### Customizing
First you'll want to fork the repo to your own account. Then clone it locally and customize, or use the GitHub web editor to customize.

#### Options/configuration

Since this is a resume *manager*, some setup is needed. The point here is that you can make several resumes with minimal work, so the defaults need to be filled in here. More info on making individual resumes is included below.

The global customizations (name, contact info, etc.) will take place in the /_config.yml file, and will show on all resumes. Here is a list of the global customizations available via /_config.yml:

-	**Baseurl:** Leave blank to run locally, or fill in with your gh-pages url if serving from there.
o	`baseurl: “(leave blank, or add gh-pages url)”`
-	**Resume Name:** Enter your name here, as it will show in the header of each resume.
o	`resume_name: Your Name`
-	**resume_header_links:** Enter your contact information here, so that the header links will automatically navigate to the correct pages. Un-comment any links to exclude them.
o	`resume_header_links:
  resume_header_email: "somebody@somewhere.org"
  resume_header_phone: "123-456-7891"
  resume_header_linkedin: "https://www.yourlinkedin.com/"
  resume_header_github: "https://yourgithub.com/"`
-	**Resume Sections:** These are the sections that will appear in *every* resume by default. Comment out any sections that you know you will not want in **any** of your resumes. NOTE: If you do not fill in any entries for a section for a particular resume, then that section will not be included in that resume only. (I recommend leaving all these un-commented.)
-	**Default Front-Matter:** These key-value pairs control which entries from your dataset will be included in the current resume they reside in, and so they **_MUST_** be copied to every resume document within the `resumes/` directory. Editing the front matter is explained later in this document, in the “Building a Resume” section.

## Data
The `_data/` directory in the project root will hold all of your employment-related data, and serve as a database from which the `layout: resume` type documents will build individual resumes. There are 5 ‘entry-categories’ in this resume template and each has a single data-file within the `_data/` directory:
1. **about:** Your impact statement or general personal intro.
2. **education:** Your education history and achievements.
3. **projects:** Projects that you have worked on that are relevant to work experience.
4. **skills:** Your work-related skills (soft, technical, etc.)
5. **work:** Your work history

Note that these files will contain ALL of your relevant work data, so if you are building resumes for multiple different jobs that require different (for example) work experience, include all of your work history, as you will be able to individually select which entries show in which resume (more on that later on 😊).

As just mentioned, each data-file will need to be filled out. I have outlined here just how to do that.

### About


## Building a Resume




Editing content
Most of the content configuration will take place in the /_layouts/resume.html file. Simply edit the markup there accordingly

Publishing to GitHub Pages for free
GitHub Pages will host this for free with your GitHub account. Just make sure you're using a gh-pages branch, and the site will automatically be available at yourusername.github.io/resume-template (you can rename the repo to resume for your own use if you want it to be available at yourusername.github.io/resume). You can also add a CNAME if you want it to be available at a custom domain...

Configuring with your own domain name
To setup your GH Pages site with a custom domain, follow the instructions on the GitHub Help site for that topic.

Themes
Right now resume-template only has one theme. More are coming 🔜 though. ❤️

Roadmap
A feature roadmap is available here. If you features suggestions, please open a new issue.

Contributing
If you spot a bug, or want to improve the code, or even make the dummy content better, you can do the following:

Open an issue describing the bug or feature idea
Fork the project, make changes, and submit a pull request
License
The code and styles are licensed under the MIT license. See project license. Obviously you should not use the content of this demo repo in your own resume. 😉

Disclaimer: Use of Homer J. Simpson image and name used under Fair Use for educational purposes. Project license does not apply to use of this material.a
