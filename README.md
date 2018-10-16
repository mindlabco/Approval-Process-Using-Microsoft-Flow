# Flow Configuration Image
![Dlow Configuration Image](https://github.com/mindlabco/Approval-Process-Using-Microsoft-Flow/blob/master/Flow%20Configuration%20Image.png)

# Approval Process Using Microsoft Flow

When New Item is created into SharePoint list, Approval Flow will start and Triggers the Microsoft Flow for the Approval Process of newly created Item. An Email will be send to the Manager for Approve/Reject. After Approval flow will send an Email to the User and Updates the Approval Status value based on the Response of the Manager.

# Working Procedure

When an Item is Created into the Tasks list.
![Task List](https://github.com/mindlabco/Approval-Process-Using-Microsoft-Flow/blob/master/Task%20List.png)

Approval Process will start and Sends the Email to the Approver for Approve/Reject the Item.
![Approval Process Mail](https://github.com/mindlabco/Approval-Process-Using-Microsoft-Flow/blob/master/Approval%20Mail.png)

After the approval we'll send an Email to creator of the Item to Notify that Item is Approved or Rejected.
![Confirmation Email](https://github.com/mindlabco/Approval-Process-Using-Microsoft-Flow/blob/master/Mail.png)

And at the last step Flow will update the Approval Status column to Approve/Reject as per the Approvers action and insert the comments of the Approver into the SharePoint list.
![Updated Task List](https://github.com/mindlabco/Approval-Process-Using-Microsoft-Flow/blob/master/List%202.png)
