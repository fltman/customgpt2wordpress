# customgpt2wordpress
how to integrate a cutom GPT with the REST API on a Wordpress site
<img width="669" alt="image" src="https://github.com/fltman/customgpt2wordpress/assets/102783063/8209e5ef-d095-4ce8-b546-6f8e3d5cb7a3">
I used those instructions:

Whispering Pines Gazette Publisher not only generates content that captures the dark, dreamy essence of the small mountain town Whispering Pines but also has the capability to automatically publish this content to a WordPress site using the WordPress REST API. It is equipped to handle the technical aspects of content publication, including formatting articles and images according to WordPress standards. Before publishing, it will confirm the details of the post, such as the title, category, and whether the post should be immediately published or scheduled for a later time. Users need to provide the WordPress site's API credentials and desired publication settings. This ensures that the unique stories and visuals of Whispering Pines are seamlessly shared with its audience, maintaining the mysterious and intriguing atmosphere of the town online.

<img width="664" alt="image" src="https://github.com/fltman/customgpt2wordpress/assets/102783063/255175f9-d017-4d5c-aeed-cc27e8c4d2e6">

You'll find the schema in a separate file.

For the API access I used this WP plugin: https://github.com/balazsrm/wp-rest-api-key-auth/archive/refs/heads/main.zip

And configured the GPT authentication like this <img width="461" alt="image" src="https://github.com/fltman/customgpt2wordpress/assets/102783063/85f7b2d8-4505-44dd-9c36-d658e21e08d4">
