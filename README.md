gsn
===



import frappe, os
if not os.path.exists(os.path.join(frappe.local.site_path, 'private', 'files')):
          frappe.create_folder(os.path.join(frappe.local.site_path, 'private', 'files'))


