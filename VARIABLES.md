## Common Variables

<table border="1">

<thead>

<tr>

<th>cemt_var</th>

<th>default</th>

<th>help</th>

<th>cemt_type</th>

</tr>

</thead>

<tbody>

<tr>

<td>agreement_is_esign</td>

<td>true</td>

<td>Indicates if it is esign vs sign, default of true indicates an esign document</td>

<td>control</td>

</tr>

<tr>

<td>agreement_pages</td>

<td>1</td>

<td>Indicates number of pages in the agreement, default is 1</td>

<td>number</td>

</tr>

<tr>

<td>agreement_thumbnail_image_path</td>

<td>/images/no-attachments-thumbnail.png</td>

<td>Indicates the image path for the agreement thumbnail in the email, default is path to blank page thumbnail</td>

<td>string</td>

</tr>

<tr>

<td>agreement_titlecasename</td>

<td>Test Agreement</td>

<td>Indicates title of the agreement in title case, e.g. "Test Agreement"</td>

<td>string</td>

</tr>

<tr>

<td>all_get_attachments</td>

<td>true</td>

<td>Indicates whether all parties get final copy by email. Refer to SEND_EMAIL_ATTACHMENTS == EVERYONE in Adobe Sign admin settings for more details.</td>

<td>control</td>

</tr>

<tr>

<td>all_get_signedandfiledemail</td>

<td>true</td>

<td>Indicates if all get signed and filed email or not. Refer to SEND_SIGNED_AND_FILED_EMAIL == EVERYONE in Adobe Sign admin settings for more details.</td>

<td>control</td>

</tr>

<tr>

<td>allow_agreement_thumbs</td>

<td>true</td>

<td>Indicates whether thumbnails are allowed in the email. Refer to EMAIL_ALLOW_AGREEMENT_THUMBS in Adobe Sign admin settings for more details.</td>

<td>control</td>

</tr>

<tr>

<td>disable_aftersign</td>

<td>false</td>

<td>Whether to show text after document is signed. Refer to DISABLE_EMAIL_NOTICE_AFTER_SIGN in Adobe Sign admin settings for more details</td>

<td>control</td>

</tr>

<tr>

<td>following_signers_set</td>

<td></td>

<td>List of email addresses (or their display email if email is not set) of all the remaining signers grouped by their signer sets.</td>

<td>array</td>

</tr>

<tr>

<td>following_signers_set_size</td>

<td>0</td>

<td>Indicates number of groups of remaining signer sets.</td>

<td>number</td>

</tr>

<tr>

<td>footer_image</td>

<td>null</td>

<td>Indicates the path to the footer image. Refer to EMAIL_FOOTER_IMAGE_FILENAME Adobe sign admin setting for more details.</td>

<td>string</td>

</tr>

<tr>

<td>from</td>

<td>echosign</td>

<td>Tells the local part of from address e.g. if from address is xyz@echosign.com, it's value would be xyz</td>

<td>string</td>

</tr>

<tr>

<td>from_title</td>

<td>Adobe Sign</td>

<td>Indicates title of from address e.g. if from address is mr xyz <xyz@echosign.com>, it's value would be mr xyz</xyz@echosign.com></td>

<td>string</td>

</tr>

<tr>

<td>header_image</td>

<td>null</td>

<td>Tells the path to the header image in the email. Gets the value from EMAIL_HEADER_IMAGE_FILENAME admin setting. If that's not set, it gets value from LOGO_FILENAME admin setting.</td>

<td>string</td>

</tr>

<tr>

<td>hide_safe_list</td>

<td>false</td>

<td>If specified show hide the user safe email address message. Refer to EMAIL_HIDE_SAFELIST in Adobe Sign admin settings for more details.</td>

<td>control</td>

</tr>

<tr>

<td>image_url_prefix</td>

<td>https://secure.na1.echosign.com</td>

<td>Indicates the URL prefix for images in email</td>

<td>string</td>

</tr>

<tr>

<td>is_protected</td>

<td>false</td>

<td>Indicates if agreement is password protected</td>

<td>control</td>

</tr>

<tr>

<td>is_originator</td>

<td>false</td>

<td>Indicates if receiver is originator</td>

<td>control</td>

</tr>

<tr>

<td>is_delegate</td>

<td>false</td>

<td>Indicates if receiver is a delegate</td>

<td>control</td>

</tr>

<tr>

<td>is_observer</td>

<td>false</td>

<td>Indicates if receiver is an observer</td>

<td>control</td>

</tr>

<tr>

<td>lastparticipant_fullnameandcompanyoremail</td>

<td>J Doe (Some other company)</td>

<td>Indicates full name and company (or email if that's not set) of last or most recent participation. null if there is no participation till now.</td>

<td>string</td>

</tr>

<tr>

<td>lastparticipant_fullnameandemail</td>

<td>J Doe (jdoe@someothercompany.com)</td>

<td>Indicates full name and email of last or most recent participation. null if there is no participation till now.</td>

<td>string</td>

</tr>

<tr>

<td>originator_fullnameoremail</td>

<td>J Smith</td>

<td>Indicates full name (or email if that's not set) of originator</td>

<td>string</td>

</tr>

<tr>

<td>originator_fullnameandcompanyoremail</td>

<td>J Smith (Some Company)</td>

<td>Indicates full name and company (or email if that's not set) of originator</td>

<td>string</td>

</tr>

<tr>

<td>pages_expected</td>

<td>1</td>

<td>Indicates number of expected pages of the agreement. Only relevant for Fax workflows. For others, it tells the page count of the document.</td>

<td>number</td>

</tr>

<tr>

<td>pages_received</td>

<td>1</td>

<td>Indicates number of received pages of the agreement. Only relevant for Fax workflows. For others, it tells the page count of the document.</td>

<td>number</td>

</tr>

<tr>

<td>participation_role</td>

<td>SIGNER</td>

<td>Participation role of the receiver</td>

<td>choice</td>

</tr>

<tr>

<td>reply_to</td>

<td>jsmith</td>

<td>Indicates local part of reply-to address e.g. if address is xyz@somecompany.com, it's value would be xyz.</td>

<td>string</td>

</tr>

<tr>

<td>reply_to_domain</td>

<td>somecompany.com</td>

<td>Indicates domain part of reply-to address e.g. if address is xyz@somecompany.com, it's value would be somecompany.com.</td>

<td>string</td>

</tr>

<tr>

<td>reply_to_title</td>

<td>J Smith</td>

<td>Indicates title of reply-to address</td>

<td>string</td>

</tr>

<tr>

<td>retention_period</td>

<td>-1</td>

<td>Indicates the document retention period in days. If corresponding setting is not set or is set to RETAIN_FOREVER, returns -1\. Refer to DOCUMENT_RETENTION Adobe Sign admin setting for more details.</td>

<td>number</td>

</tr>

<tr>

<td>tracking_id</td>

<td>453453454334534</td>

<td>Tells the tracking id for the given email. It is the index of email record for this email in Adobe Sign database.</td>

<td>number</td>

</tr>

<tr>

<td>secure_tracking_id</td>

<td>CBFCIBAA3AAABLKmtbUARK7fYgfBjzPUKOJ3tGSqIr9FjkwolmuIZhaaND4Rscb0s_wZ22MbQX60DyzCcRiY*</td>

<td>Indicates the secure tracking id for the given email</td>

<td>string</td>

</tr>

<tr>

<td>settings_email_account_signature</td>

<td>Confidentiality Notice: The contents of this e-mail (including any attachments) may be confidential to the intended recipient, and may contain information that is privileged and/or exempt from disclosure under applicable law. If you are not the intended recipient, please immediately notify the sender and destroy the original e-mail and any attachments (and any copies that may have been made) from your system or otherwise. Any unauthorized use, copying, disclosure or distribution of this information is strictly prohibited.</td>

<td>Tells email signature message set for the account. Refer to EMAIL_ACCOUNT_SIGNATURE Adobe Sign admin setting for more details.</td>

<td>string</td>

</tr>

<tr>

<td>settings_email_allow_individual_signature</td>

<td>false</td>

<td>Indicates if individual signature is allowed. Refer to EMAIL_ALLOW_INDIVIDUAL_SIGNATURE in Adobe Sign admin settings</td>

<td>control</td>

</tr>

<tr>

<td>settings_email_user_signature</td>

<td>null</td>

<td>Tells email signature message set for the user. Refer to EMAIL_USER_SIGNATURE in Adobe Sign admin settings for more details</td>

<td>string</td>

</tr>

<tr>

<td>settings_logo_filename</td>

<td>null</td>

<td>Indicates the logo filename from settings. Refer to LOGO_FILENAME in Adobe Sign admin settings for more details</td>

<td>string</td>

</tr>

<tr>

<td>unescaped_agreement_titlecasename</td>

<td>Test Agreement</td>

<td>Unescaped agreement title. Used in the subject of the email</td>

<td>string</td>

</tr>

<tr>

<td>debug_dump</td>

<td>null</td>

<td>Debug Dump of all replacement variables and their values</td>

<td>string</td>

</tr>

<tr>

<td></td>

<td> </td>

<td> </td>

<td> </td>

</tr>

</tbody>

</table>

## Please Sign Variables

<table border="1">

<thead>

<tr>

<th>cemt_var</th>

<th>default</th>

<th>help</th>

<th>cemt_type</th>

</tr>

</thead>

<tbody>

<tr>

<td>please_sign_delegator_fullnameoremail</td>

<td>J Smith</td>

<td>Indicates full name (or email if that's not set) of delegator. If there is no delegator, returns these details of the originator.</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_intendedsigner_fullnameoremail</td>

<td>null</td>

<td>Tells full name (or email if that's not set) of person who was originally intended to sign this agreement. If there was no delegation, this value is null.</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_delegator_fullnameandcompanyoremail</td>

<td>J Smith (Some Company)</td>

<td>Indicates full name and company (or email if that's not set) of delegator. If there is no delegator, returns the details of the originator.</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_intendedsigner_fullnameandcompanyoremail</td>

<td>null</td>

<td>Tells full name and company (or email if that's not set) of person who was originally intended to sign this agreement. If there was no delegation, this value is null.</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_sibling_nameoremails</td>

<td>jdoe@someothercompany.com</td>

<td>Comma separated list of names of email addresses of all participations in the receiver's Recipient Group including the receiver. If there is no Recipient Group, it just includes the details of the receiver.</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_sibling_nameoremails_size</td>

<td>1</td>

<td>Size of the list of names of email addresses of all participations in the receiver's Recipient Group including the receiver. If there is no Recipient Group, size is either 0 or 1.</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_delegation_message</td>

<td>null</td>

<td>Tells the text which was used while delegating the agreement</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_agreement_message</td>

<td>Please review and sign this agreement</td>

<td>Tells the text which was used as agreement message</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_agreement_private_message</td>

<td>null</td>

<td>Tells the text of the private message specified in the agreement</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_attached_documents</td>

<td></td>

<td>List of names of documents to be attached while signing the agreement. These are attachment fields which are added by the originator while sending the agreement.</td>

<td>array</td>

</tr>

<tr>

<td>please_sign_attached_documents_size</td>

<td>0</td>

<td>Tells size of array of attached documents with each entry being the name of the attached document. If there are no documents to be attached while signing, value is 0.</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_failed_auto_delegatee</td>

<td>null</td>

<td>If auto delegation failed for a particular delegatee, indicates the details of that delegatee. Otherwise null.</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_auto_delegation_failed_reason</td>

<td>null</td>

<td>If auto delegation failed for a particular delegatee, indicates the reason why it failed. Otherwise null.</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_is_written_signer</td>

<td>false</td>

<td>Tells if the receiver has been asked to do written signature.</td>

<td>control</td>

</tr>

<tr>

<td>please_sign_agreement_sequential</td>

<td>true</td>

<td>Tells if it's a sequential flow agreement or not</td>

<td>control</td>

</tr>

<tr>

<td>please_sign_esign_link</td>

<td>https://secure.na1.echosign.com/public/esign?tsid=CBFCIBAA3AAABLKmtbUAGNZUZLA5W2qaMhSR5rYycf8vjjVENSqFGgpcFGaKrmH81oVAfC5O8cfoVxrLakQT8OPVnOYg55ru5l4mt25GE&</td>

<td>Contains the fully qualified link to sign this agreement. Value is null if receiver cannot sign the agreement.</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_can_be_delegated</td>

<td>true</td>

<td>Tells if agreement can be delegated</td>

<td>control</td>

</tr>

<tr>

<td>please_sign_has_digital_signature_field</td>

<td>false</td>

<td>Tells if paricipation has digital signature field</td>

<td>control</td>

</tr>

<tr>

<td>please_sign_resend_link</td>

<td>https://secure.na1.echosign.com/public/resend?tsid=CBFCIBAA3AAABLKmtbUBzwU5UfIiMLP-wNeLXmsJPJLBcPAgjKkMuh8QabO733QsFm7HsxmcxHasEPBJDvmVWlFAOMHd_dwD7lyMzUtvj</td>

<td>Contains the fully qualified link to delegate this agreement. Value is null if agreement cannot be delegated.</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_expiration_date</td>

<td>null</td>

<td>Tells the expiration date for taking an action on this agreement. Value is null if there is no expiration.</td>

<td>string</td>

</tr>

<tr>

<td>please_sign_user_can_sign</td>

<td>true</td>

<td>Tells if the receiver can sign this agreement. Refer to USER_CAN_SIGN in Adobe Sign admin settings for more details.</td>

<td>control</td>

</tr>

<tr>

<td>please_sign_originator_first</td>

<td>false</td>

<td>Tells if the originator is the first person to sign this agreement. It is true if Add me was clicked while sending the agreement and originator was specified to sign the agreement first.</td>

<td>control</td>

</tr>

<tr>

<td>please_sign_originator_last</td>

<td>false</td>

<td>Tells if the originator is the last person to sign this agreement. It is true if Add me was clicked while sending the agreement and originator was specified to sign the agreement last.</td>

<td>control</td>

</tr>

<tr>

<td></td>

<td> </td>

<td> </td>

<td> </td>

</tr>

</tbody>

</table>

## Signed And Filed Variables

<table border="1">

<thead>

<tr>

<th>cemt_var</th>

<th>default</th>

<th>help</th>

<th>cemt_type</th>

</tr>

</thead>

<tbody>

<tr>

<td>signed_and_filed_allow_name</td>

<td>true</td>

<td>Tells whether Signed and Filed email should have the user or company name in the subject and title. Refer to SHOW_NAME_IN_SIGNED_AND_FILED_EMAIL Adobe Sign admin setting for more details.</td>

<td>control</td>

</tr>

<tr>

<td>signed_and_filed_user_gets_attachments</td>

<td>true</td>

<td>Tells whether the recipient of Signed and Filed email should get attachment. Refer to SEND_EMAIL_ATTACHMENTS Adobe Sign admin setting for more details.</td>

<td>control</td>

</tr>

<tr>

<td>signed_and_filed_can_view_agreement</td>

<td>true</td>

<td>Tells whether the recipient of Signed and Filed email can view agreement. It is always true if recipient is a participant in the agreement.</td>

<td>control</td>

</tr>

<tr>

<td>signed_and_filed_show_viewacopy_link</td>

<td>true</td>

<td>Tells whether the Signed and Filed email should contain view a copy link. Refer to SHOW_VIEW_A_COPY_LINK_IN_EMAIL Adobe Sign admin setting for more details.</td>

<td>control</td>

</tr>

<tr>

<td>signed_and_filed_demarketEmails</td>

<td>false</td>

<td>Tells whether the Signed and Filed email should be stripped of the marketing content. Refer to DEMARKET_EMAILS Adobe Sign admin setting for more details.</td>

<td>control</td>

</tr>

<tr>

<td>signed_and_filed_is_megasign</td>

<td>false</td>

<td>Tells whether the agreement being signed was part of a Megasign.</td>

<td>control</td>

</tr>

<tr>

<td>signed_and_filed_all_parties</td>

<td>jsmith@somecompany.com,jdoe@someothercompany.com</td>

<td>List of full names (or their emails if full name is not set) of each party involved in the agreement. For originator, it can include his or her company name.</td>

<td>array</td>

</tr>

<tr>

<td>signed_and_filed_to_list_text</td>

<td>jdoe@someothercompany.com</td>

<td>List of full names (or their emails if full name is not set) of each allowed user to be put in the body of Signed and Filed email. Refer to SEND_SIGNED_AND_FILED_EMAIL_TO_ORIGINATOR and SEND_SIGNED_AND_FILED_EMAIL Adobe Sign admin settings for more details.</td>

<td>array</td>

</tr>

<tr>

<td>signed_and_filed_cc_list_text</td>

<td></td>

<td>List of full names (or their emails if full name is not set) of each allowed CC user to be put in the body of Signed and Filed email. List is picked up from the Ccs on the agreement.</td>

<td>array</td>

</tr>

<tr>

<td>signed_and_filed_current_signers_set</td>

<td></td>

<td>List of email addresses (or their display email if email is not set) of each signer who needs to sign this agreement after the most recent signer.</td>

<td>array</td>

</tr>

<tr>

<td>signed_and_filed_agreement_flow_samePhaseAsMostRecentSigned</td>

<td>true</td>

<td>Tells whether the agreement is in the same phase as most recent signing. It would be false if there are no signers left to sign in this phase.</td>

<td>control</td>

</tr>

<tr>

<td>signed_and_filed_agr_link</td>

<td>https://echosign.com/public/viewAgreement?tsid=CBFCIBAA3AAABLKmtbUCmx-lR4bXHD0FhZfF7pHZkrNd3S12LESHD73VkFZiFLYRntUCoNi5MGw3CUJylrEq2Kx-IbFlunmoZ43hbZVb2&</td>

<td>Link to view the agreemeent. In case of Megasign, it is a link to the parent agreement.</td>

<td>string</td>

</tr>

<tr>

<td>signed_and_filed_report_link</td>

<td>null</td>

<td>Link to the report of Megasign. Null if not a Megasign.</td>

<td>string</td>

</tr>

<tr>

<td>signed_and_filed_remaining</td>

<td>null</td>

<td>Tells number of remaining signers in a Megasign. null if None remain or if not a Megasign.</td>

<td>string</td>

</tr>

<tr>

<td>signed_and_filed_recipient_count_multicast</td>

<td>-1</td>

<td>Tells total number of recipients in a multicast agreement. -1 if not a multicast.</td>

<td>number</td>

</tr>

<tr>

<td>signed_and_filed_signed_count</td>

<td>-1</td>

<td>Tells number of recipients who signed the agreement in a multicast. -1 if not a multicast.</td>

<td>number</td>

</tr>

<tr>

<td>signed_and_filed_declined_count</td>

<td>-1</td>

<td>Tells number of recipients who declined the agreement in a multicast. -1 if not a multicast.</td>

<td>number</td>

</tr>

<tr>

<td></td>

<td> </td>

<td> </td>

<td> </td>

</tr>

</tbody>

</table>

## Reminder Variables

<table border="1">

<thead>

<tr>

<th>cemt_var</th>

<th>default</th>

<th>help</th>

<th>cemt_type</th>

</tr>

</thead>

<tbody>

<tr>

<td>agrlink</td>

<td></td>

<td>Link to view the agreement.</td>

<td>string</td>

</tr>

<tr>

<td>attached_document_names</td>

<td>[]</td>

<td>Array of names of documents to be attached when signing.</td>

<td>array</td>

</tr>

<tr>

<td>bound_workflow_is_pure_sequential</td>

<td>false</td>

<td>Is the workflow purely sequential, with no parallel branches?</td>

<td>control</td>

</tr>

<tr>

<td>demarket_emails</td>

<td>false</td>

<td>Should the email be stripped of the marketing content? Refer to DEMARKET_EMAILS Adobe Sign admin setting for more details.</td>

<td>control</td>

</tr>

<tr>

<td>document_retention_days</td>

<td>-1</td>

<td>Number of days the document will be available, or -1 if it will remain available indefinitely.</td>

<td>number</td>

</tr>

<tr>

<td>originator_full_name</td>

<td>J Smith</td>

<td>Full name of the agreement originator.</td>

<td>string</td>

</tr>

<tr>

<td>reminder_frequency</td>

<td>ONCE</td>

<td>How often the reminder will be sent. One of the following values: WEEKDAILY, DAILY, WEEKLY, DAILY_UNTIL_SIGNED, WEEKLY_UNTIL_SIGNED, ONCE.</td>

<td>string</td>

</tr>

<tr>

<td>reminder_note</td>

<td>Let me know if you still have any questions. Thanks!</td>

<td>Note added by the user sending the reminder.</td>

<td>string</td>

</tr>

<tr>

<td>stop_link</td>

<td></td>

<td>Link for the recipient to stop receiving reminder emails.</td>

<td>string</td>

</tr>

<tr>

<td>subtype</td>

<td>reminder_next_to_esign</td>

<td>Which type of reminder this email represents. One of the following values: reminder_signed, reminder_next_to_esign, reminder_next_to_sign, reminder_not_next_to_esign, reminder_not_next_to_sign.</td>

<td>string</td>

</tr>

<tr>

<td>user_full_name_or_email</td>

<td>J Doe</td>

<td>The user's full name or email address.</td>

<td>string</td>

</tr>

<tr>

<td></td>

<td> </td>

<td> </td>

<td> </td>

</tr>

</tbody>

</table>

## Canceled Variables

<table border="1">

<thead>

<tr>

<th>cemt_var</th>

<th>default</th>

<th>help</th>

<th>cemt_type</th>

</tr>

</thead>

<tbody>

<tr>

<td>comment</td>

<td>This was all a mistake and I need to cancel.</td>

<td>Comment added by canceler.</td>

<td>string</td>

</tr>

<tr>

<td>agreement_data_parties_names</td>

<td>John Doe</td>

<td>A list of names on the agreement.</td>

<td>array</td>

</tr>

<tr>

<td>any_exposed</td>

<td>true</td>

<td>Toggles additional text in email indicating document has been deleted from all parties accounts.</td>

<td>control</td>

</tr>

<tr>

<td>canceler_full_name_and_company_or_email</td>

<td>John Doe (spacex)</td>

<td>The cancelers name and company or email.</td>

<td>string</td>

</tr>

<tr>

<td>cancel_type</td>

<td>self</td>

<td>Indicates the type of cancellation based on the workflow. Choices: self, signer_to_signers, originator_to_signers, originator_to_unsigned_exposed, signer_to_originator</td>

<td>choice</td>

</tr>

<tr>

<td>notify</td>

<td>true</td>

<td>Toggles additional text in email indicating parties have been notified of cancel.</td>

<td>control</td>

</tr>

<tr>

<td>refusal_category</td>

<td>sender_cancel</td>

<td>Indicates the reason the agreement was canceled. Choices: prefer_fax, refuse, other, sender_cancel</td>

<td>choice</td>

</tr>

<tr>

<td>canceler_participation_role</td>

<td>SIGNER</td>

<td>Role of the participant that canceled the agreement. Choices: SIGNER, APPROVER, FORM_FILLER, ACCEPTOR, CERTIFIED_RECIPIENT, DELEGATE_TO_SIGNER, DELEGATE_TO_APPROVER, DELEGATE_TO_FORM_FILLER, DELEGATE_TO_ACCEPTOR, DELEGATE_TO_CERTIFIED_RECIPIENT</td>

<td>choice</td>

</tr>

<tr>

<td></td>

<td> </td>

<td> </td>

<td> </td>

</tr>

</tbody>

</table>
