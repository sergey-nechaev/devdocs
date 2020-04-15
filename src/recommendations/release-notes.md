# Release notes for Product Recommendations

The following updates describe the latest improvements to Product Recommendations.

The release notes include:

-  {:.new}New features
-  {:.fix}Fixes and improvements

## 2.0.0

This release is compatible Magento Commerce 2.3.3+.

-  {:.new}<!-- MC-15250 -->Added explicit product sorting to the Products content type.

-  {:.new}<!-- MC-17823 -->Added buttons for inserting images, widgets, and variables in the HTML content type.

-  {:.fix}Improved Page Builder security.

-  {:.fix}<!-- MC-1805 -->Updated Page Builder to support PHP version 7.3.

-  {:.fix}<!-- MC-4137 -->Updated TinyMCE to version 4.9.5. This update, along with our additional improvements, fixed several TinyMCE inline editor issues:

   -  {:.fix}Variables, images, & image links now get added where the cursor is place.
   -  {:.fix}Tables and table cells can now be center aligned.
   -  {:.fix}Copy/paste now pastes content at the cursor's position.
   -  {:.fix}Links can now be applied to selected text.
   -  {:.fix}Bullets are now properly aligned.
   -  {:.fix}Changes within the inline editor can now be saved without first clicking outside the editor.

-  {:.fix}<!-- MC-3880 -->Fixed an issue in which the minimum height & vertical alignment was inconsistent between sections on the edit panel for each content type.

-  {:.fix}<!-- MC-14994 -->Fixed an issue in which the toolbar from the Heading content type was positioned incorrectly when first dropped on the stage.

-  {:.fix}<!-- MC-15742 -->Fixed hard-coded margins in both Slider and Video content types.

-  {:.fix}<!-- MC-16241 -->Fixed an issue in which the required asterisk symbol was displayed twice on form fields.

### Documentation

To learn more about Product Recommendations:

-  For developers: [Product Recommendations Developer Guide](https://devdocs.magento.com/recommendations/product-recs.html)
-  For end-users: [Product Recommendations User Guide](https://docs.magento.com/m2/ee/user_guide/marketing/product-recommendations.html)
