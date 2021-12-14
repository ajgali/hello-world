<?php
/**
 * The base configuration for WordPress
 *
 * The wp-config.php creation script uses this file during the installation.
 * You don't have to use the web site, you can copy this file to "wp-config.php"
 * and fill in the values.
 *
 * This file contains the following configurations:
 *
 * * MySQL settings
 * * Secret keys
 * * Database table prefix
 * * ABSPATH
 *
 * @link https://wordpress.org/support/article/editing-wp-config-php/
 *
 * @package WordPress
 */

// ** MySQL settings - You can get this info from your web host ** //
/** The name of the database for WordPress */
define( 'DB_NAME', 'appZiemann_1639497899' );

/** MySQL database username */
define( 'DB_USER', 'appZiemann_1639497899' );

/** MySQL database password */
define( 'DB_PASSWORD', 'password' );

/** MySQL hostname */
define( 'DB_HOST', 'ajswp.holbrookasphalt.com' );

/** Database charset to use in creating database tables. */
define( 'DB_CHARSET', 'utf8mb4' );

/** The database collate type. Don't change this if in doubt. */
define( 'DB_COLLATE', '' );

/**#@+
 * Authentication unique keys and salts.
 *
 * Change these to different unique phrases! You can generate these using
 * the {@link https://api.wordpress.org/secret-key/1.1/salt/ WordPress.org secret-key service}.
 *
 * You can change these at any point in time to invalidate all existing cookies.
 * This will force all users to have to log in again.
 *
 * @since 2.6.0
 */
define('AUTH_KEY',         '_CF; J3uYw~qoms3WYjJR`h127xK|y@JSW~]E*tC2=Pqv5t.D4!43<+qm&$9MP;E');
define('SECURE_AUTH_KEY',  'UMM@IVvR/VK[q-cw>8Dzj0pI}e7g>IPx^H#J1kmQQV -V1a;k7Wr~7LX{XF`R@pm');
define('LOGGED_IN_KEY',    '!dOksT1()vLAanMT.zO3gLC@=agK fk<u*2e+|O(Vt&_v7eS=w-lES*+BC>|OAR{');
define('NONCE_KEY',        'i0zdGn];j9w$PZlz9s)*xpA %cwb=.B o5ttX|zt0*jx%%<^<p}]RROS~_=`.d 1');
define('AUTH_SALT',        ',3{ q%hQ:hv/#X/;uv~7w7ww~4t1P2l+cW~rK-q#rlzc!Ec2.ExxcW-|RW|!5L/,');
define('SECURE_AUTH_SALT', '$(>`HR#n |BH=CJYYR7yB9-@QF:@RxkP@?-([{ECvY,L-XG6=QbJJn=T+hZ0c-$I');
define('LOGGED_IN_SALT',   'pCUN9+fE9XFkC}]7_8;~5]~:hXEM7-Q}|:S0lz7>=dI7D9yM_$l1wvWVC!u20<5a');
define('NONCE_SALT',       'JJ>b=Zima(HiH)fx}lM-QpI;ee-!/+uR[N/_vr=w=-fItvwv/)/h-V |nv5?M?|W');
/**#@-*/

/**
 * WordPress database table prefix.
 *
 * You can have multiple installations in one database if you give each
 * a unique prefix. Only numbers, letters, and underscores please!
 */
$table_prefix = 'wp_';

/**
 * For developers: WordPress debugging mode.
 *
 * Change this to true to enable the display of notices during development.
 * It is strongly recommended that plugin and theme developers use WP_DEBUG
 * in their development environments.
 *
 * For information on other constants that can be used for debugging,
 * visit the documentation.
 *
 * @link https://wordpress.org/support/article/debugging-in-wordpress/
 */
define( 'WP_DEBUG', false );

/* Add any custom values between this line and the "stop editing" line. */


/* That's all, stop editing! Happy publishing. */

/** Absolute path to the WordPress directory. */
if ( ! defined( 'ABSPATH' ) ) {
        define( 'ABSPATH', __DIR__ . '/' );
}

/** Sets up WordPress vars and included files. */
require_once ABSPATH . 'wp-settings.php';


