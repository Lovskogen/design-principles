# Product Design Principles

## These principles is to make sure a product interface is of high quality

1. **Strong visual hierarchies** with clear understanding of viewing order, layout, size and colour contrast.

2. **Smart organisation** by grouping like elements, show relationships by placement and orientation.

3. **Colour to highlight** not for backgrounds or branding, optimise for readability and attention to key elements.

4. **Good empty states** where blank views should have a clear primary action and description, providing direction and guidance. Not a blank space with zero understanding.

5. **Good defaults** with the most likely option already selected (based on use or by design) to decrease workload, informative placeholder text in fields describing what to put in, placeholder text should disappear once field is active and should never the be the only place that requirements for a field (if any) is shown.

6. **System status should always be visible** to the user through feedback, like showing a loading graphic and message, buttons changing states after being clicked, feedback messages when an action has been successfully done - to confirm.

7. **Real world language using metaphors**, concepts and words familiar to the users rather than system-oriented terms. An example being "Create New Case" instead of "Create New Folder" or "Create New Collection".

8. **Consistency in language, words, concepts** - not having different names for the same object in different places of the system. Consistency with interface patterns for desktop/tablet/mobile. Consistency in iconography based on established standards, not creating bespoke icons for the interface. Consistency in how interface elements behave, ex. support as-you-type for ‘name’ fields everywhere, not just one place.

9. **Navigation should be clear** and be supported by a visual hierarchy. There should be a logical placement of navigation, not a tab navigation that will change content above the tabs or navigate to a new page.

10. **Error prevention before error messages**, eliminate error prone conditions or validate before a user can submit. 

11. **Error messages should be written in plain language** (no codes), precisely indicate the problem and constructively suggest a solution.

12. **Recognition over recall**, minimise the users memory load by making objects, actions and options visible, user should not have to remember information from one part of the interface to another. An example of this is as-you-type input fields, or the in-line preview of fonts in Word's font drop-down. In case items might be hard to recall based on just the name, a selection list could show more metadata to make it easier to separate and choose the right one.

13. **Minimal design and aesthetic**, dialogues should not contain information which is irrelevant and rarely needed. Visual layouts should respect the principles of contrast, repetition, alignment and proximity. An example being colours only used to highlight primary actions or primary areas, brand colour should not affect readability and main work areas.

14. **Help information should be easy to search**, focused on the user’s task, list concrete steps to be carried out, and not be too large. Inline help should be used where possible, ex. by input elements or explaining a primary action.

15. **Smart use of computer**, being able to understand inputs to fields and having no need for one exact input format ex. "Phone numbers must only include numbers".

16. **Latency reduction should be hidden** to users through multitasking techniques, letting them continue with their work while transmission and computation takes place in the background. Make sure the interface does not jump and jitter as information is finally loaded and shown. Acknowledge all button clicks by visual feedback within 50ms, trap multiple clicks of the same button or object. Example, uploading a large video file should not freeze the interface to continue uploading smaller files, writing meta data and saving. The ongoing upload should warn the user of any action (like logout or window close) that will terminate the upload.

17. **Application responsiveness should be fast**, by returning search results in maximum 3 seconds, completing a login in maximum 3 seconds and loading individual screens in maximum 2 seconds.

18. **Use large objects for important functions** (big buttons are faster), use small objects for functions you would prefer users not to perform. Use Fitt's law in placing interface elements, but also reduce the total number of targets that must be acquired to carry out a task.

19. **Track and save state**. The system should know if this is the first time the user has been in the system, where the user left off in the last session. When the log off state should be saved, for when they later login and want to continue their work.

20. **Protect users' work**. Never reset a whole form due to one invalid field. Temporarily save work in case the user loses network connection or power, let them pick up once they are back.

21. **Optimise for readability**. Favour black text on white or pale backgrounds. Avoid grey backgrounds. Favour particular large font-size for the actual data you intend to display, as opposed to labels and instructions, ex. the label "Last Name" can afford to be somewhat small while the input field should not be. Make sure the typeface used for the interface and its content is widely recognised as good typefaces in those areas.

22. **Stay on the page**. Modern web applications does not need to navigate to different "pages". This also helps in not blocking users to continue work while a particular large tasks (like uploading a large video) is happening in the background..

23. **Leverage common interface design patterns**. By doing so you are giving the users familiar elements which they already have experienced and common patterns that have already been tested and optimised.

24. **Use iconography with caution** and always have a text label. Do not produce custom icons to be used in the interface, as the users will not know what they mean. Use standard icons to communicate meaning and reduce ambiguity.

25. **Support undo actions** instead of asking for confirmation. "are you sure..?" is the antithesis of considerate behaviour. Follow design patterns for undo like that of GMail’s undo functionality.

26. **Responsive layout**. To cater for a variety of screen sizes without making users scroll horizontally.

27. **Support a range of browsers**, latest version of Firefox, Safari, Chrome and Internet Explorer.

28. **Support multiple devices**. For this type of administrative work, support tablets and laptop computers.

29. **Accessibility standards**. Adhere to WCAG 2.0 AA.

30. **Support most common assistive technology** JAWS 15 or later on IE11, ZoomText 10.11 or later on IE11, Dragon NaturallySpeaking 11 or later on IE11, NVDA 2016 or later on latest Mozilla Firefox, VoiceOver 7.0 or later in Safari on iOS 10 and OS X.
