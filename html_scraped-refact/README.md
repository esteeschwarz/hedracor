# 13375.info
- this folder contains basic TEI essais on (should contain more than 1) refactoring the webscraped text from here: <https://benyehuda.org/read/33373>
- horsing around with different text endpoints (id's) lead to code errors, so the TEI of the one text is now again not properly output; i am aware of these errors and fix them since the basic text of (33373) seems to be okay and so the script should be able to reformat all in that consistent benyehuda texts to this simple dracor scheme.

#### notes:
- danil: i found that its important to replace (or escape) anführungszeichen (i dont know the name, its not really a double yud, i think its abbreviations?) instances like in these: /ד"ר גרי – רופא
/ by /''/ e.g. so that the \<speaker\> declaration for instance is properly tagged in an element like \<sp who="..."\> if the speaker contains these anführungszeichen.

# 16133.2025-03-23(10.25).review requested(cmil)
- received review request, didnt know permissions? i figure out...
- consulted action fail (tei validate: mostly xmlid issues)
  - cloned, try push this readme changes (to chk my permissions)
  - tested: no permissions, pushed to fork.