1)
profile_image = document.querySelector('.profile-image')
profile_image.src = 'https://placebear.com/400/400'

1)
sky_image = document.querySelector('#left-image  img')
sky_image.src = 'https://picsum.photos/325/225'

2)
heading = document.querySelector('h1')
heading.innerText = 'Stephen Varela'

3)
employment_heading = document.querySelector('#employment .info-title')
employment_heading.innerText = 'FuntastikTings'

4)
body = document.querySelector('body')
body.style.backgroundColor = 'yellow'

5)
highlight_class_elements = document.querySelectorAll('.highlight')
highlight_class_elements.forEach(function(element){
    element.style.backgroundColor='green'
})

6)
main_heading = document.querySelector('h1')
main_heading.style.fontFamily = 'monospace'

7)
round_icons = document.querySelectorAll('.action-icon-bg')
round_icons.forEach(function(item){console.log(item.style.backgroundColor='red')})
8)
contact_form_name = document.querySelector('#name');
contact_form_name.placeholder='Check yo self';

9)
contact_form_message = document.querySelector('#message');
contact_form_message.placeholder = 'What is your business here';

10)
contact_form_name = document.querySelector('#name');
contact_form_name.value='Your nemesis';

11)
contact_form_email = document.querySelector('#email')
contact_form_email.value='koalathebear@gmail.com'

12)
submit_button = document.querySelector('#submit')
submit_button.value='En Guard'

13)
contact_form_message = document.querySelector('#message');
contact_form_message.disabled='true'

14)
