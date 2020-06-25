# mailchimp-signupform-for-wordpress
HTML and CSS for an inline MailChimp signup form which can be embedded into WordPress. This form contains the fields for first name, last name and email address. If you need to customise the form fields, just make sure that the attributes of the HTML elements (i.e. type, value, name, class, id) match the fields of your MailChimp mailing list's fields.

Instructions:

#1 Copy and paste the code in mailchimp-signupform-for-wordpress.html into a HTML component/widget on your WordPress target page/area. I.e. on the Home page, or under Appearance/Widgets. 

Note: if you intend to use this form on a WordPress website, I recommend placing the HTML code in an in-grid HTML component/page builder widget, within a full-width row, on a full-width page. It is recommended to use a full-width parallax background image on the row with around 150px padding above and below the form section. Usually, you'd also place a title and paragraph copy encouraing the user the sign up.

Example of section layout:

    Full width page 
        Full width row with parallax backround image (Image size +- 1920px by 700px;)
            In-grid row with 150px top and bottom padding
                Title
                Padding (16px)
                Paragraph
                Padding (32px)
                Form

#2 Copy and paste the code in style.css into your Child Theme's stylesheet, and edit accordingly for your own colors, fonts, borders etc.

#3 Inside the form's HTML code, look for: 

    form action="ENTER YOUR MAILCHIMP FORM URL HERE" 
    
Replace "ENTER YOUR MAILCHIMP FORM URL HERE" with your own MailChimp form's target URL.

You now have an inline signup form!!
