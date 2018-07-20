# GIFT-google-quiz-plugin
**GIFT Quiz Editor** was created to help instructors create quizzes with the [GIFT syntax](https://en.wikipedia.org/wiki/GIFT_\(file_format\)).

GIFT is a short, intuitive and normalized syntax used originally in the Moodle community to create quiz questions.
It allows storing quiz questions in a textual format that can be versionned, shared and easily modified.

Several aspects of GIFT are not fully supported, because Google's Quizzes and its API are limited in functionality.

This project was done by Jonathan G.V. under the supervision of [Christopher Fuhrman](https://etsmtl.ca/Professeurs/cfuhrman/Accueil?lang=en-CA) 
during a special project in the fall semester of 2017 at [École de technologie supérieure (ETS) Montréal](https://www.etsmtl.ca). 

It uses a parser generated by [PEG.js](https://pegjs.org) from the [GIFT grammar in PEG.js](https://github.com/fuhrmanator/GIFT-grammar-PEG.js). 

You can submit issues, requests and comments on this github repository.

## Privacy policy / Permissions

I, Jonathan Girard Viau, am the provider (“Provider”) of the GIFT Quiz Editor service. I respect a Clients' right to and expectation of privacy, and accordingly maintain and adhere to a rigorous privacy policy (the “Privacy Policy”).

This Privacy Policy discloses the types of personal information collected and stored by the Provider. All Clients must acknowledge and agree to the collection and use of personal information as set forth in this Privacy Policy.

### Disclosure to Third Parties

I will not use client or user information for any purposes other than to provide the GIFT Quiz Editor service.

GIFT Quiz Editor uses other services (Google Forms and peg.js) to provide its service. See their privacy policies for more information.

### Permissions

When you install GIFT Quiz Editor in Google Forms, you will be asked to grant permissions. Sadly, you're not told _why_ those permissions are needed. This is an explanation of why (to the best of my knowledge) they are needed.

| Permission | Why it's needed |
|------------|-----------------|
| View and manage documents that this application has been installed in | GIFT Quiz Editor can delete and insert questions in your Google Form. |
| View and manage data associated with the application | GIFT Quiz Editor saves settings (such as the current GIFT code for the form) on the google server.|
| Allow this application to run when you are not present| GIFT Quiz Editor uses an authentication scheme (OAuth) that uses tokens, and these tokens can be refreshed when you're not present.