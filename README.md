firestarter
===========

## Installation

1. Download the latest version. Comes in .zip archive format
1. Unzip the package into target location
1. Edit application/config/config.php and set base URL:

 $config['base_url']	= 'firestarter.local';

(If you intend to use encryption or sessions, you can set your encryption key)

1. Edit application/config/database.php and set your database settings:

 $db['default']['username'] = 'root';
 $db['default']['password'] = 'root';
 $db['default']['database'] = 'codeigniter';

NOTE: I personally find CodeIgniter documentation lacking in precision, as well as user friendliness. The bare bones approach for maximum performance is commendable, but makes concise documentation even more valuable and required for wider framework adoption.

NOTE 2: The design decision not to use templates is purely for performance, but expect people to cringe.

