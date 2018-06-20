+++
date = "2018-06-20T19:02:14+00:00"
draft = true
recipient = "survey-answers@example.com"
submit_text = ""
title = "Survey"
[[sections]]
title = "Your Information"
[[sections.fields]]
label = "Full Name"
name = "name"
template = "text-field"
type = "text"
[[sections.fields]]
label = "E-mail Address"
name = "email"
template = "text-field"
type = "text"
[[sections.fields]]
label = "Your Role"
name = "role"
options = ["Content Creator", "Designer", "Developer", "Manager"]
template = "select"
type = "select"
[[sections]]
title = "User Experience"
[[sections.fields]]
label = "How easy was it use the app?"
name = "ease_of_use"
options = ["1 (not easy)", "2", "3", "4", "5 (very easy)"]
template = "radio"
type = "radio"
[[sections.fields]]
label = "How useful did you find the documentation?"
name = "doc_usefulness"
options = ["1 (not useful)", "2", "3", "4", "5 (very useful)"]
template = "radio"
type = "radio"
[[sections.fields]]
label = "Is there anything we can do to make our app easier to use?"
name = "ux_suggestions"
template = "textarea"
type = "textarea"
[[sections]]

+++
