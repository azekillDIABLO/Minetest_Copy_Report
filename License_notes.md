#About licenses

These notes are written by an Open Source and Libre Software enthusiast, not by an actual lawyer. The interpretation below is subject to corrections.

However, it stands to make sure that if you report an app, you understand what the app is violating, and what it is not

## About copyright holding

As a community member, you can report any app to this list.

HOWEVER!!

You must not report violations to the Google Play store unless you are the copyright holder of an asset in question.

Only the copyright holder can make representations on their license, and can waive the copyright for any specifc user at their personal discretion.

## Minetest : LGPL v2

The license text is at [https://www.gnu.org/copyleft/lesser.html](https://www.gnu.org/copyleft/lesser.html)

The following section is of most relevance to our efforts:


	4. Combined Works.

	You may convey a Combined Work under terms of your choice that, taken together, effectively do not restrict modification
	of the portions of the Library contained in the Combined Work and reverse engineering for debugging such modifications,
	if you also do each of the following:

	    a) Give prominent notice with each copy of the Combined Work that the Library is used in it and that the Library and
		its use are covered by this License.
	    b) Accompany the Combined Work with a copy of the GNU GPL and this license document.
	    c) For a Combined Work that displays copyright notices during execution, include the copyright notice for the Library
		among these notices, as well as a reference directing the user to the copies of the GNU GPL and this license document.
	    d) Do one of the following:
		0) Convey the Minimal Corresponding Source under the terms of this License, and the Corresponding Application Code
		 in a form suitable for, and under terms that permit, the user to recombine or relink the Application with a modified
		version of the Linked Version to produce a modified Combined Work, in the manner specified by section 6 of the GNU GPL
		 for conveying Corresponding Source.
		1) Use a suitable shared library mechanism for linking with the Library. A suitable mechanism is one that (a) uses at
		 run time a copy of the Library already present on the user's computer system, and (b) will operate properly with a
		 modified version of the Library that is interface-compatible with the Linked Version.
	    e) Provide Installation Information, but only if you would otherwise be required to provide such information under
		section 6 of the GNU GPL, and only to the extent that such information is necessary to install and execute a modified
		version of the Combined Work produced by recombining or relinking the Application with a modified version of the Linked
		Version. (If you use option 4d0, the Installation Information must accompany the Minimal Corresponding Source and
		Corresponding Application Code. If you use option 4d1, you must provide the Installation Information in the manner
		specified by section 6 of the GNU GPL for conveying Corresponding Source.)


A common misconception is that Free Software must be provided free of charge. This is NOT true. The app publisher must provide the source code to the portions under GPL, however that does not mean they cannot sell compiled versions. Do not report an app if it is pay-for but the author otherwise complies with all other requirements of the license. See RedHat Enterprise Linux as an example of this practice.

Minetest itself is under Lesser GPL which means that Minetest code itself, and any code directly derived from it, is covered by the LGPL license and must be made available. However it does not mean that any other code distributed with it also needs to be under the same license.

## Many mods: WTFPL

The "Do Whatever the F You Want Public License" [http://www.wtfpl.net/faq/](http://www.wtfpl.net/faq/)

Any mods released under this license are not required to receive attribution, as per the terms of the license. Do not include un-atttributed mods under the WFTPL license as examples of offences.

## Some mods: BSD 2-clause and 3-clause

Attribution in the source code is required, and in legal representaions and descriptions.

However, no marketing-level attribution is needed, or attribution in documentation.

## Many media: Creative Commons

[https://creativecommons.org/](https://creativecommons.org/)

The mods licensed under Creative Commons are the ones that will need most attention.

Firstly, the CC licenses were not designed for code in mind. Use BSD, APache, GPL etc licenses instead where you can.

Other than that, there are seevral traits for CC licenses:

1. BY - the core license requirement, attribution is ALWAYS required for CC-licensed items
2. ND - "No Derivatives" : the work can be included/packaged in other works, but the licensed work itself must remain unchanged.
	* If the mod's code or media has been adjusted, the mod must be removed or reverted to the original form
3. NC - "Non Commercial" : the work cannot be used in a commercialized product.
	* If the app is pay-for or ad-supported, the work must not be used in the app
4. SA - share alike : the licensed work must be distributed with the same permissions as provided to the author of the new work
	* This should cover the mod itself, not the app packaging the mod, though I am not sure this is clear.
