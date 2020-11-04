# HTML5-CSS3
work on adding custom css and javascript
call to action
make connext box work

A video 
Contact form, with Call To Action
A gallery of photos
Reviews or Quotes (about the Durango area)
Make it mobile responsive (bonus points a mobile-specific menu)

adding custom css to your Divi project.
Divi is a wonderful theme builder inside of wordpress, that makes making websites a breeze.
And while it covers just about everything you can think of, every once in a while you might 
need to write a little css or javascript of your own. Today i would like to discuss covering just that.

Thankfully, adding css to your project is relatively easy with Wordpress Divi, and there are a number of ways this can be accomplished, lets take a look.

Inline CSS.
    Added to any Divi module within the theme with a content area. To add inline css
    to a section of an element, you will need to target the element itself and the style attribute. From here you can add any styling property that relates to the specific element you're trying to target. Just assign assign a tag to an element and apply the style. It is a very quick fix for any of your css needs, but this mean you have to add style to every element. This is very time consuming and easy to forget a single style applied.


Custom CSS Box
    One popular way to add your own custom css is to use the Divi custom CSS box, found in the Divi Theme Dashboard. To find the exact property that you need to target, you can simply open the specific Divi module. Just navigate to the advanced tab and click in the main element and the name will pop up just above the text. To go a level deeper for more children within the element, simply add a selector. This is great for a handful of css edits and a little easier to find, and is not overridden by theme updates. Only downfall is this method does not include any formatting assistance, like a code editor for instance.

Advanced options tab 
    Using the advanced options tab to add our css. The big plus here is you can add a unique class or id. Another incentive is you have to include the selector,just the property and value. While the sections don’t have too many options, the rows present plenty of styling options. Adding CSS into the modules and rows can be useful for quick, simple edits, but beyond small changes that are going to stay the same forever, adding CSS this way isn’t really recommended. While this is useful for adding quick styles, this can become confusing or forgotten do the line, when working with a big website.

Divi Builder Page Settings
    This is hands down the best way to apply styles to single or multiple pages. Divi Builder Page Settings let users adjust variables per page without having to adjust each individual modules. You can find this custom CSS box within the Divi Page Builder Settings. With this we get split testing, custom color picker, set the pages gutter width, and a few more options. Here it is important to specify the selector that you want to target, since this is more of a page based approach. downfall here is you might loose track of your styling if you have many pages on your website, as well as the limited formatting features, as we've seen thus far.


Divi child theme style.css file
    This could possibly be the best way to add custom css to your website, with a unique children stylesheet. Beyond simply having the CSS styling in the same place, our custom websites created for clients tend to get a bit complicated, and thus, we need the ability to reference multiple stylesheets. To get started with a child theme, we recommend using our Divi Space child theme Child Theme Generator. To get started with a child theme, we recommend using our Divi Space child theme Child Theme Generator. All you have to do is enter your details and the details relating to the website you’re building and your child theme will be mailed to you. Once you’ve downloaded your Div child theme, you can install it on your website by navigating to Appearance > Themes and clicking Add New. Then, click Upload Theme and select the Divi child theme from your downloads folder. Install the child theme as you did the parent, click activate, and in no time, you’ll be running a child theme to protect your Divi website. Once installed and activated, you can make changes to the stylesheet by navigating to Appearance > Editor, and selecting the style.css file from the child theme itself. Using a child theme and stylesheet will allow you to use and enqueue multiple stylesheets. Even if you were to successfully add CSS styling to the parent theme, your changes would be overridden everytime a new theme update would be released. To help safeguard your website and preserve your CSS changes, use a child theme and enter your CSS into a stylesheet. This method is the most complicated to set up and is the least user-friendly of the above-mentioned methods


Add CSS with WordPress plugins
    Plugins are a great way to add CSS because they don’t require any special coding. Simply install a WordPress plugin and you can start adding your CSS. There are lots of good options available in both free and premium versions. Unfortunately i can't go into great detail here, as there are very many options and all vary depending on how they were made, and what features they include. Many include great interfaces that highlight the syntax. You can see the styling before publishing your code, and you don't have to modify your themes files. A big downfall here is if the developer stops ubdating the plugin, you will have to replace it with another. Plugins have tendency to slow down your website.
    
    
These are the main ways to add CSS to your website. Having quite a few options, it's not hard to find a way to add css the way you need for the occasion you need.
