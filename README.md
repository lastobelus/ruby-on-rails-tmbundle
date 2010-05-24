#Rails TextMate Bundle

##Description

Features I've added to the bundle include:

####Shoulda Support
 * Full shoulda support WITHOUT having to swap your active bundle.  This allows you to continue using the Rails bundle, but still all the advantages of my Shoulda bundle:
   * syntax highlighting, 
   * ability to run tests and contexts from textmate
   * shoulda snippets and commands
   * <code>⌘⇧+T</code> lists shoulda tests / contexts

####Other Changes
 * <code>⌥+:</code> aligns code (ie if you have a hash on multiple lines, you can easily align all the keys with the first key)
 * <code>⌥⇧+M</code> opens a window of recent migrations with links to open the migration file
 * <code>⌥⇧+L</code> lets you easily  open or tail rails logs (development, test, production) 
 * <code>rest⇥</code> - snippets for rest named routes (you'll never need to pull out that rest cheatsheet again!)
 * <code>⌘⇧+T</code> lists factory names (when file includes Factory Girl definitions)
 * Lots of other rails snippets: Rails.root, asserts, scopes, etc.  
 
##Installation

1. $ `cd ~/Library/Application\ Support/TextMate/Bundles/`
2. $ `git clone git://github.com/handcrafted/handcrafted-haml-textmate-bundle.git Haml.tmbundle`
3. $ `osascript -e 'tell app "TextMate" to reload bundles'`
 
####My Other Textmate Bundles
My bundles work best when use in conjunction with my other bundles:

 * Rails - [http://github.com/phuibonhoa/ruby-on-rails-tmbundle](http://github.com/phuibonhoa/ruby-on-rails-tmbundle)
 * Ruby - [http://github.com/phuibonhoa/ruby-tmbundle](http://github.com/phuibonhoa/ruby-tmbundle)
 * Shoulda - [http://github.com/phuibonhoa/ruby-shoulda-tmbundle](http://github.com/phuibonhoa/ruby-shoulda-tmbundle)
 * HAML - [http://github.com/phuibonhoa/handcrafted-haml-textmate-bundle](http://github.com/phuibonhoa/handcrafted-haml-textmate-bundle)
 * Sass - [http://github.com/phuibonhoa/ruby-sass-tmbundle](http://github.com/phuibonhoa/ruby-sass-tmbundle)
 * JavaScript - [http://github.com/phuibonhoa/Javascript-Bundle-Extension](http://github.com/phuibonhoa/Javascript-Bundle-Extension)
 * CTags - [http://github.com/phuibonhoa/tm-ctags-tmbundle](http://github.com/phuibonhoa/tm-ctags-tmbundle)

##Credits

Additions by [Philippe Huibonhoa](http://github.com/phuibonhoa)


Original bundle and it's contributors can be found [here](http://github.com/drnic/ruby-on-rails-tmbundle)
