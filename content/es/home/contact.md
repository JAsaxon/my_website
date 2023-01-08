+++
widget = "contact_form"
title = "Contactame" 

# Uncomment the following line and widget will NOT be displayed
# hidden = true

# Uncomments the following line for
# standard forms.
#
# Form handler
# action = "/contact_handler.php"
# Form submit method
# method = "GET" # Default is POST

# For Netlify form
#
netlify = true

# Add a contact via email button if your email
# is configured in the config file of your website.
useEmail = true

# Form inputs
[[inputs]]
label = "Tu nombre"
# Input type
type = "text"
# minimum input length
name = "name"
# pattern matching
pattern = "[a-zA-Z]+"
placeholder = "Nombre"
# The input is required to submit the form
# required = true

[[inputs]]
label = "Tu correo"
type = "email"
name = "email"
# pattern = ""
placeholder = "Correo"
required = true

# Textarea works same as input but doesn't support pattern matching
[[inputs]]
label = "Tu mensaje"
type = "textarea"
# pattern is not supported on textarea
name = "message"
placeholder = "Tu mensaje..."
required = true

+++

Estas pasando por una etapa dificil y necesitas ayuda profesional? Contactame!

