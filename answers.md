1)
var profile_image = document.querySelector('.profile-image')
profile_image.src = 'https://placebear.com/400/400'

1)
var sky_image = document.querySelector('#left-image  img')
sky_image.src = 'https://picsum.photos/325/225'

2)
var heading = document.querySelector('h1')
heading.innerText = 'Stephen Varela'

3)
var employment_heading = document.querySelector('#employment .info-title')
employment_heading.innerText = 'FuntastikTings'

4)
var body = document.querySelector('body')
body.style.backgroundColor = 'yellow'

5)
var highlight_class_elements = document.querySelectorAll('.highlight')
highlight_class_elements.forEach(function(element){
    element.style.backgroundColor='green'
})

6)
var main_heading = document.querySelector('h1')
main_heading.style.fontFamily = 'monospace'

7)
var round_icons = document.querySelectorAll('.action-icon-bg')
round_icons.forEach(function(item){console.log(item.style.backgroundColor='red')})

8)
var contact_form_name = document.querySelector('#name');
contact_form_name.placeholder='Check yo self';

9)
var contact_form_message = document.querySelector('#message');
contact_form_message.placeholder = 'What is your business here';

10)
var contact_form_name = document.querySelector('#name');
contact_form_name.value='Your nemesis';

11)
var contact_form_email = document.querySelector('#email')
contact_form_email.value='koalathebear@gmail.com'

12)
var submit_button = document.querySelector('#submit')
submit_button.value='En Guard'

13)
var contact_form_message = document.querySelector('#message');
contact_form_message.disabled='true'

14)
var details = document.querySelector('.bio-info')
var details_parent = details.parentElement
details_parent.removeChild(details)


Part 2
<!-- removing child -->
var travel_bar = document.querySelectorAll('.bar-default')[2]
var travel_parent = travel_bar.parentElement
travel_parent.removeChild(travel_bar)


<!--  clonning node-->
var node_to_clone = document.querySelector('#right-image img')
var clonned_node = node_to_clone.cloneNode();
var portfolio_container = document.querySelector('.portfolio-container')
portfolio_container.appendChild(clonned_node)

<!-- repeat 10 times -->
for(let i = 0; i < 10; i++){
  var clonned_node = node_to_clone.cloneNode();
  portfolio_container.appendChild(clonned_node)
}

<!-- Adding new HTML element-->
var listitem = document.createElement('li');
var leftspan = document.createElement('span');
var lastUpdate = document.createTextNode('Page last updated on: ');
leftspan.appendChild(lastUpdate)
listitem.appendChild(leftspan)

var rightspan = document.createElement('span')
var date = new Date()
var last_updated_time = document.createTextNode(date)
rightspan.appendChild(last_updated_time)
listitem.appendChild(rightspan)

var toAppendto = document.querySelector('.bio-info')
toAppendto.appendChild(listitem)

<!-- modify classes -->
var itemToStyle = document.querySelectorAll('.bio-info li')[3];
itemToStyle.className = 'bio-info-item'

var spansToStyle1 = document.querySelectorAll('.bio-info li span')[6];
var spansToStyle2 = document.querySelectorAll('.bio-info li span')[7];
spansToStyle1.className = "bio-info-title"
spansToStyle2.className = "bio-info-value"
