## Installing

- Start with a Drupal 10 or Drupal 11 site.
- Install whatever profile you like.
- Apply the recipe.

The recipe can be applied with PHP in Drupal 10.3+.

Execute this command from the web root:

```shell
php core/scripts/drupal recipe recipes/contrib/sofarkotta-songs
```

Or by using `ddev exec`

```shell
ddev exec -d /var/www/html/docroot php core/scripts/drupal recipe recipes/contrib/sofarkotta-songs
```

If all goes well, you should see the following output:

```shell
 [OK] Sofarkotta Songs applied successfully
```

Clear the cache after the recipe is applied. When going back to the site,
all the recipe configuration and customization has been applied.

You might want to place the `more_variations` ("További variációk") block in the content region,
below the content block, for the `song` node type pages.
