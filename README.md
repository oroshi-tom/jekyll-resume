# jekyll-resume-template
A modern-looking resume built with Jekyll and powered by Github Pages
![img](images/screenshot.png)
This template makes it easy to quickly make several custom-tailored resumes with minimum effort
(And they look cool, too 👌).
[View on GitHub Pages](https://oroshi-tom.github.io/jekyll-resume-template/)

=======
# Jekyll Resume Template/Manager
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

The global customizations (name, contact info, etc.) will take place in the `/_config.yml` file, and will show on all resumes. Here is a list of the global customizations available via `/_config.yml`:

-	**Baseurl:** Leave blank to run locally, or fill in with your GitHub Pages website URL if serving from there. [See the GitHub Pages docs](https://docs.github.com/en/github/working-with-github-pages/about-github-pages) for more information
```
baseurl: ""
```
-	**Resume Name:** Enter your name here, as it will show in the header of each resume.
```
resume_name: John Doe
```
-	**resume_header_links:** Enter your contact information here, so that the header links will automatically navigate to the correct pages. Un-comment any links to exclude them.
``` 
contact_links:
  email: "somebody@somewhere.org"
  phone: "123-456-7891"
  linkedin: "https://www.yourlinkedin.com/"
  github: "https://yourgithub.com/" 
```
-	**Resume Sections:** These are the sections that will appear in *every* resume by default. Comment out any sections that you know you will not want in **any** of your resumes. NOTE: If you do not fill in any entries for a section for a particular resume, then that section will not be included in that resume only. (I recommend leaving all these un-commented.)

## Data
The `_data/` directory in the project root will hold all of your resume and cover-letter data, and serve as a database from which the `layout: resume` and `layout:letter` type documents will build individual resumes. There are 5 ‘entry-categories’ in this resume template and each has a single data-file within the `_data/` directory:
1. **about:** Your impact statement or general personal intro.
2. **education:** Your education history and achievements.
3. **projects:** Projects that you have worked on that are relevant to work experience.
4. **skills:** Your work-related skills (soft, technical, etc.)
5. **work:** Your work history

Note that these files will contain ALL of your relevant work data, so if you are building resumes for multiple different jobs that require different (for example) work experience, include all of your work history, as you will be able to individually select which entries show in which resume (more on that later on 😊).

As just mentioned, each data-file will need to be filled out. I have outlined here just how to do that.

### About

### Education

### Projects

### Skills

### Work

## Building a Resume

## Building a Cover Letter




