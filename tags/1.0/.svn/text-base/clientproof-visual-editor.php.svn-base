<?php
/*
Plugin Name: Client-proof Visual Editor
Plugin URI: http://justhugo.com/wp-plugins/clientproof-visual-editor
Version: 1.0
Author: Hugo Baeta
Author URI: http://justhugo.com
Description: Simple, option-less, plugin to make TinyMCE - the WordPress Visual Editor - easier for clients and n00bs.
*/

function clientproof_visual_editor( $initArray ) {
	//@see http://wiki.moxiecode.com/index.php/TinyMCE:Control_reference
	$initArray['theme_advanced_blockformats'] = 'h2,h3,h4,p,dt,dd,code';
	$initArray['theme_advanced_disable'] = 'underline,justifyfull,forecolor,pasteword,media,charmap,outdent,indent,undo,redo,wp_help,justifyleft,justifycenter,justifyright,wp_adv';
	$initArray['theme_advanced_buttons1'] = 'bold,italic,strikethrough,|,formatselect,|,bullist,numlist,blockquote,|,link,unlink,wp_more,hr,|,removeformat';
	$initArray['paste_text_use_dialog'] = "false";
	$initArray['paste_auto_cleanup_on_paste'] = "true";
	return $initArray;
}
add_filter('tiny_mce_before_init', 'clientproof_visual_editor');

?>