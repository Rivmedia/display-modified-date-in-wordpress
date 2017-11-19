# Display Modified Date in wordpress Posts and Pages
Small Code snippet to change the published date,  to the modified date in wordpress posts and pages. 

```php 
<?php if (get_the_modified_time() != get_the_time()) : ?>
		Updated On: <?php the_modified_time('F j, Y'); ?> at <?php the_modified_time('g:i a'); ?>
	<?php else: ?>
		Posted on <?php the_time('F j, Y'); ?> at <?php the_time('g:i a'); ?>
<?php endif; ?>
```

Source : * [Displaying Modified Date in Wordpress Instead of Published](https://www.rivmedia.co.uk/how-to-display-the-last-modified-date-of-your-posts-in-wordpress-for-seo-freshness/4902) 
