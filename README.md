#HAML TextMate Bundle

##Description

Forked from the Handcrafted HAML TextMate Bundle.  Additions include

####Improved Language
 * Text inside ERB and Javascript filters are now properly recognized so you get all the syntax highlighting, snippets, commands, etc.
 * Added built-in html recognition. Helpful when you include html in your haml.
 * Ruby code inside <code>#{}</code> recognized as embedded ruby
 * Updated language so that < and > are recognized as HAML constants

####Added snippets and commands
 * <code>⌘⌥+C</code> converts selection from HTML to HAML (and tries to convert erb to haml style - still beta-y)
 * <code>⌃+></code> inserts <code>#{}</code> and toggles between <code>#{ruby code}</code> and <code>#{ ruby code }</code>
 * Added snippets for attributes (<code>:⇥</code> and <code>=></code>)
 * Added full trigger snippets for common html elements (ie table, br, div, h1, h2, etc.)
 * <code> ⌘+/</code> uses rails comments -# instead of HTML comments
 * <code>⌘⌥+X</code> escapes HTML special characters
 
####Other Textmate Bundles
My bundles work best when use in conjunction with my other bundles:
 * Rails - http://github.com/phuibonhoa/ruby-on-rails-tmbundle
 * Ruby - http://github.com/phuibonhoa/ruby-tmbundle
 * Shoulda - http://github.com/phuibonhoa/ruby-shoulda-tmbundle
 * HAML - http://github.com/phuibonhoa/handcrafted-haml-textmate-bundle
 * Sass - http://github.com/phuibonhoa/ruby-sass-tmbundle
 * JavaScript - http://github.com/phuibonhoa/Javascript-Bundle-Extension
 * CTags - http://github.com/phuibonhoa/tm-ctags-tmbundle

##Credits

Additions by [Philippe Huibonhoa](http://github.com/phuibonhoa)

Original 

##Installation

1. $ `cd ~/Library/Application\ Support/TextMate/Bundles/`
2. $ `git clone git://git://github.com/phuibonhoa/ruby-on-rails-tmbundle.git Rails.tmbundle`
3. $ `osascript -e 'tell app "TextMate" to reload bundles'`

##Original Bundle Contributors
#### Rails 3.0 contributors

* Kamil Kukura (rake migrate timestamp patch)

#### Rails 2.0 features/contributors (copied from CHANGELOG)

* Snippets/Commands for:
  * Tests
    * assert_select (ass)
    * assert_difference/assert_no_difference (asd/asnd)
    * GET+POST test method stubs (defg+defp)
  * Controllers
    * respond_to (rst)
    * REMOVED: render_component snippets
    * loggers - pass a block instead of raw string to save time if logging not used (e.g. production) [thx Stephen Touset]
    * redirect_to for resource paths (rep, repp, renp, renpp)
    * render :update (ru) [thx Simon Jefford]
  * Views
    * form_for (ff)
    * link_to for resource paths (lip, lipp, linp, linpp)
    * <% end -%> (end)
  * Models
    * has_many :though (hmt)
    * association snippets give better defaults (e.g. bt + hm)
    * validates_format_of (vf,vfif) [thx Dean Strelau]
  * Migrations
    * Sexy Migrations now available as "t." snippets [thx Lawrence Pit]
    * Migration classes have own textmate scope
    * Add/Remove Columns - the 'down' statements are in reverse order [thx Lawrence Pit, Daniel Kristensen]
* Language/Syntax
  * New keywords: rescue_from
  * Added rb as a valid Rails file type [thx James Deville]
* Commands
  * html.erb is the default for new templates (backwards compatibility is being worked on too)
* Plugins
  * Footnote
    * footnote-edge uses .erb for templates [thx Stephen Bannasch]

* Ian's extra notes:
  * I've noticed that the install plugin command doesn't work under Ruby 1.9.*