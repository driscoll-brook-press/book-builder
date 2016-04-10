---
title: Copyright Information
guide: copyright-information
...
{% assign publisher = site.data.publisher %}
{% assign publication = site.data.publication %}

## {{ publication.title }}

ISBN: {{ publication.isbn.ebook }}

Published by [{{ publisher.name }}]({{ publisher.url }})

{% for claim in publication.rights
%}{{ claim.material }} &copy; {{ claim.date }} {{ claim.owner }}{%
  unless forloop.last %}<br />{% endunless %}{%
endfor %}

This ebook is licensed for your personal enjoyment only.
This ebook may not be re-sold or given away to other people.
If you would like to share this book with another person,
please purchase an additional copy for each recipient.
If you're reading this book and did not purchase it,
or it was not purchased for your use only,
then please return to your favorite ebook retailer
and purchase your own copy.
Thank you for respecting the hard work of this author.

All rights reserved.
No part of this book may be reproduced or used in any manner
without the express written permission of the publisher
except for the use of brief quotations in a book review.

This is a work of fiction.
Names, characters, businesses, places, events and incidents
are either the products of the author's imagination
or used in a fictitious manner.
Any resemblance to actual persons, living or dead, or actual events
is purely coincidental.
