In odoo page is inside of record element, and pages are created by the means of xml and html.

To create controls inside a page we define it by using field element and other incorporating xml and/or html elements

The name attribute within the element plays a big part on how an element will turn out
	eg. <field name="name"> Course </field> => will act as a label
	<field name="res_model">openacademy.course</field> => will define the model the page is connected or using
	<field name="view_type">form</field> => will define the type of page
	<field name="view_mode">tree,form</field> => will define how the browser perceived the page contents
	<field name="help" type="html">
	<p class="oe_view_nocontent_create"> ... </p>
	</field> => will display an html element with eye catching css that can hellp users for navigation