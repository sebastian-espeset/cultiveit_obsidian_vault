## Github project links
- [Adding other](https://github.com/Cultiveit/cultiveit-api/issues/187)
- [Adding "Im not feeling burntout"](https://github.com/Cultiveit/cultiveit-api/issues/188)
## Adding Other:
### Research
#### *What is being asked?*
	add functionality that lets a user add their own reason for being burnout.
		1. select other
		2. add the reason in a text box
		question: **do we save that in db somewhere and make it an option for later use??**
#### *Where is it in the codebase?*
- API → slack → templates → `share_feedback_modal_template.py`
#### *What should happen?*
- User selects other
- New modal with just a text box?
- What do we do with the new info?