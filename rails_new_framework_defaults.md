(Reference new_framework_defaults_X_Y.rb file)

I added this file.

Create a new plans doc in docs/plans/new_framework_defaults_X_Y.md in GitHub-flavored Markdown with checkboxes.

Add this to the plans doc and write it:

Do the following for each commented config line:
 - Do a detailed, slightly paranoid search of the codebase to see if our application would potentially be impacted by this change. If so / if not, update the plans doc with your findings
 - Uncomment a **single** config line
 - Make a new commit of format:
    - load_defaults 6.0: \<Few words describing the config change\>
 - always keep the plans doc updated
 - do not commit the plans document

Be sure to work one config at a time.
