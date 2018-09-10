# Best-Practices-for-files

Naming for front end development is very important to keep everything organized. Here's some best practices I use to keep development running quickly and smoothly.

## Only Use Lowercase Letters
As soon as you start incorporating capital letters, you have 52 letters to worry about in front end development instead of 26. It gets confusing for developers to remember which words are capitalized and when.

Good	logo_version_a.png
Bad	LogoVersionA.png
 
Good | logo_version_a.png | 
--- | --- | 
Bad | LogoVersionA.png |

## Underscores, Spaces or Dashes? 
Never use special characters such as spaces in your filename. In short, browsers have to encode the special characters ( | & ~ ¡ etc) into something it can read. For example, the [space] character will be encoded to "%20". You don't want to make your front end developer have to type in %20 everytime you press spacebar. That's inneficiant and it looks sloppy.

As for spaces and hyphens, that's up to the designer/developer. As a rule of thumb, I use the "_" underscore to distinguish elements and the "-" hyphen to separate words of the same element. 

Good | homepage_drupal-logo.png | 
--- | --- | 
Bad | homepage%20drupallogo.png |

## General to specific 
This really helps keep files organized within the directory both locally and online. Now your folder will be visually organized by icons, buttons, backgrounds, etc...

Good | icon_homepage_help.png | 
--- | --- | 
Bad | help_icon_homepage.png |

#### Example: 
![alt text](https://github.com/shah0150/Best-Practices-for-files/blob/master/Picture1.png)


# Date and Time
Occasionally you will want to attach a date to a picture. Again, you will want to go from general to specific here to keep your files organized. If you start with the month, then items from August 2004 will appear before items from January 2013 in your folder.

For dates, use *YYYYMMDD* (year; month; day) and for times use *HHMMSS* (hour; minute; second).

Good | blueprint_progress_2013-01-23 | 
--- | --- | 
Bad | blueprint_progress_jan_23_2013 |

# Don't Overdo It
Keep file names short, clear, and meaningful. Understand that the longer the filenames are, the more the developers have to type to write your image into the theme.

Also, this is not the place to try to sneak in SEO keywords into your filename. It won't help anything. Trust me, if your filename is meaningful and clear enough, Google will find it.

Good | footer_icon_facebook.png | 
--- | --- | 
Bad | footer_social-block_social-media-icon_facebook.png |
Horrifying | professional_drupal_development_connect_social_media_facebook.png |

# Versions 
Often you will need different sizes of the same image. Put the version information at the end of the file, not the beginning. This will keep all of your files together in the folder (see image above)

Good | logo_sm.png; logo_med.png; logo_lg.png | 
--- | --- | 
Bad | small_logo.png; medium_logo.png; logo_large.png |

# Be Consistent 
No matter what you do with your filenaming, just make sure you are consistent. Because I am so consistent in my filenaming, front-end development can almost guess what my files are going to be named before they even see them. This speeds up production significantly. Anything you can do to save time and keep your code small, do it.

