# White-Horse-Template

![stability-wip](https://img.shields.io/badge/stability-work_in_progress-lightgrey.svg?style=flat-square) ![CircleCI](https://img.shields.io/circleci/project/github/barbajs/barba/master.svg?style=flat-square) ![CoverageStatus](https://img.shields.io/coveralls/github/barbajs/barba/master.svg?style=flat-square) ![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square) ![AllContributors](https://img.shields.io/badge/All%20Contributors-1-orange.svg) ![version](https://img.shields.io/badge/Version-1.0.1-blue.svg) ![status](https://img.shields.io/pypi/status/ansicolortags.svg)  ![Documentation](https://readthedocs.org/projects/ansicolortags/badge/?version=latest) ![GitHubforks](https://img.shields.io/badge/Fork-0-blue.svg)               ![Githubstars](https://img.shields.io/badge/Star-0-blue.svg) ![GitHubwatchers](https://img.shields.io/badge/Watch-0-blue.svg) ![GitHub followers](https://img.shields.io/badge/Followers-0-blue.svg)
 ![Only3 Mb](https://img.shields.io/badge/size-3MB-green.svg) ![Open Source Lovesvg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)

White-Horse is a free to use Bootstrap template.

This template uses the default Bootstrap 4 styles along with a variety of powerful jQuery plugins and tools to create a

Basic HTML Template.



## Theme Demo


![White-Horse-Template](Theme-Preview/White-Horse-Template-Preview.png)



## Contact Form


This Theme Include a Basic Contact Form With Jquery Validation. Having Input Fields Name, Email, Mobile Number, Subject and Message.

 
### Contact Form Preview


![White-Horse-Template](Theme-Preview/Contact-Form-Preview.png)

### Contact Form Code
```
<form action="" method="post" role="form" class="contactForm">
	<div class="form-group">
		<input type="text" name="name" class="form-control input-text" id="name" placeholder="Your Name" data-rule="minlen:2"
                                    data-msg="Please enter at least 2 chars" />
		<div class="validation"></div>
	</div>
	<div class="form-group">
		<input type="email" class="form-control input-text" name="email" id="email"
                                    placeholder="Your Email" data-rule="email" data-msg="Please enter a valid email" />
		<div class="validation"></div>
	</div>
	<div class="form-group">
		<input type="number" class="form-control input-text" name="Mobile" id="Mobile"
                                    placeholder="Your Mobile Number" data-rule="minlen:10"
                                    data-msg="Please enter a valid Mobile Number" />
		<div class="validation"></div>
	</div>
	<div class="form-group">
		<input type="text" class="form-control input-text" name="subject" id="subject"
                                    placeholder="Subject" data-rule="minlen:5"
                                    data-msg="Please enter at least 5 chars of subject" />
		<div class="validation"></div>
	</div>
	<div class="form-group">
		<textarea class="form-control input-text text-area" name="message" rows="5"
                                    data-rule="required" data-msg="Please write something for us"
                                    placeholder="Message"></textarea>
		<div class="validation"></div>
	</div>
	<div class="text-center">
		<button type="submit" class="input-btn">Send Message</button>
	</div>
</form>
```


## Theme Details

White-Horse is a Basic HTML Template with Bootstrap Included. It is a one page Theme does not contain multiple pages. It is very Basic and Classy Template made by our Team.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
  
## Scripts included:

* Bootstrap  

* Font Awesome

* jQuery

* Validator - HTML Form Validator using jQuery
 
## Updates


### Update 1.0.0

* Template Generated

### Update 1.0.1
* Jquery Form Validation Included in Contact Form
* Mobile Number Field Inserted in Contact Form
* Readme Updated