# atom-acf-snippets
[ATOM] - Github's text editor - Snippets for Advanced Custom Fields

#How to use
Simply go to File -> Snippets and snippets.cson should open in your Atom editor, if it doesn't, you need to manually create it inside .atom folder
Paste code from line 23, save file and that's it!

Now go to your html or php file, and type for example:

acf-flex -> and press tab (so it's acf-flex + tab) and that will produce:
<?php if( have_rows('flexible_content_field_name') ): ?>
    <?php while ( have_rows('flexible_content_field_name') ) : the_row(); ?>
        <?php if( get_row_layout() == 'layout_name' ): ?>

        <?php endif; ?>
    <?php endwhile;?>
<?php endif; ?>

No more manually writing loops or needing to go to ACF doc page and copy/paste code. Make your own snippets like that, just concatenate to my code like I did ([ACF]... is beginning of new snippet).
