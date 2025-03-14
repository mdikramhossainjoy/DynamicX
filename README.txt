=== DynamicX ===
Contributors: mdikramhossainjoy
Tags: dynamic fields, WooCommerce, custom fields, product fields, WordPress plugin
Requires at least: 5.0
Tested up to: 6.7
Requires PHP: 7.2
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/old-licenses/gpl-2.0.html

== Description ==

DynamicX is a WordPress plugin designed to extend WooCommerce functionality by allowing store owners to add dynamic custom fields to their products. These custom fields can be used to display additional information about the product on the single product page, enhancing the shopping experience for customers.

This plugin is ideal for businesses that need to showcase specific details about their products that are not covered by default WooCommerce fields.

== Features ==

- Dynamic Custom Fields: Add as many custom fields as needed for each product.
- User-Friendly Interface: Easily manage custom fields through a metabox in the product edit screen.
- Frontend Display: Automatically displays custom fields on the single product page.
- Styling Options: Includes basic CSS for both admin and frontend views, ensuring a clean and professional appearance.
- AJAX-Free Functionality: No need for AJAX; all operations are handled via JavaScript for simplicity and performance.

== Installation ==

1. Download the plugin ZIP file from the GitHub Releases page.
2. Log in to your WordPress admin dashboard.
3. Navigate to Plugins > Add New.
4. Click the "Upload Plugin" button.
5. Select the downloaded ZIP file and click "Install Now".
6. Once installed, click "Activate" to enable the plugin.
7. To verify installation, go to any product edit page under Products > All Products and look for the "Custom Fields" metabox.

== Usage ==

Adding Custom Fields:
1. Edit a product by navigating to Products > All Products and selecting the desired product.
2. Locate the "Custom Fields" metabox on the product edit screen.
3. Use the "Add Field" button to create new custom fields.
4. Enter the field name in the "Text" input and its corresponding value in the "Value" input.
5. Save the product to store the custom fields.

Viewing Custom Fields:
Once added, the custom fields will automatically appear on the single product page under the product summary section.

== Customization ==

Admin Styles:
The plugin includes basic CSS for styling the custom fields metabox in the admin area. You can override these styles by adding your own CSS to the admin_enqueue_scripts hook or by modifying the plugin's code directly (not recommended).

Frontend Styles:
The plugin also includes basic CSS for displaying custom fields on the frontend. To customize the appearance, you can enqueue your own styles using the wp_enqueue_scripts hook or modify the plugin's code.

JavaScript:
The JavaScript for dynamically adding and removing custom fields is included inline in the custom_admin_script method. If you wish to enhance or modify this functionality, consider moving the script to an external file and enqueuing it properly.

== Contributing ==

We welcome contributions to improve DynamicX! Here's how you can help:

1. Report Issues: If you encounter any bugs or have suggestions, please open an issue on the GitHub Issues page.
2. Submit Pull Requests: If you'd like to contribute code, fork the repository, make your changes, and submit a pull request.
3. Documentation: Help improve the documentation by suggesting edits or additions.

== License ==

This plugin is released under the GNU General Public License v2.0 (or later).
The full license can be found at: https://www.gnu.org/licenses/old-licenses/gpl-2.0.html

== Support ==

For support, please visit the following resources:

- GitHub Repository: https://github.com/mdikramhossainjoy/DynamicX
- Author Website: https://mdikramhossainjoy.com
- Documentation: https://mdikramhossainjoy.com/docs/DynamicX

If you need further assistance, feel free to reach out to the author at contact@mdikramhossainjoy.com.
