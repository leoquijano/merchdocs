---
title: Customer Groups
---

Customer groups determine which discounts are available and the tax class that is associated with the group. The default customer groups are General, Not Logged In, and Wholesale.

<!--{% if "Default.B2B Only" contains site.edition %}-->
The selection of customer groups includes all regular customer groups, and shared catalogs, even if [Shared Catalogs]({% link stores/b2b-features.md %}) is not enabled in the configuration. Only one customer group or shared catalog can be assigned to a [company]({% link customers/account-companies.md %}) at a time.

<!--{% endif %}-->
<!--{% if "Default.CE Only" contains site.edition %}-->
![]({% link images/images/customer-groups.png %}){: .zoom}
<!--{% endif %}-->
<!--{% if "Default.EE Only" contains site.edition %}-->
![]({% link images/images/customer-groups.png %}){: .zoom}
<!--{% endif %}-->
<!--{% if "Default.B2B Only" contains site.edition %}-->
![]({% link images/images-b2b/customer-groups.png %}){: .zoom}
<!--{% endif %}-->
_Customer Groups_

## To filter customer groups:

1. On the _Admin_ sidebar, go to **Customers** > **Customer Groups**.

1. Click <span class="btn"> Filters </span>.

1. Enter criteria for searching groups, including a range of IDs, group, or tax class.

    ![]({% link images/images/customer-groups-filters.png %}){: .zoom}
    _Filtering Options_

1. When complete, click <span class="btn"> Apply Filters</span>.

    The page displays the subset of filtered customer groups and members.

## To create a customer group:

1. On the _Admin_ sidebar, go to **Customers** > **Customer Groups**.

1. Click <span class="btn"> Add New Customer Group </span>.

    - Enter a unique **Group Name** less than 32 characters to identify the group.

    - Select the **Tax Class** that applies to the group.

    ![]({% link images/images/stores-customer-group-information.png %}){: .zoom}
    _Group Information_

1. When complete, click <span class="btn">Save Customer Group</span>.

## To edit a customer group:

1. On the _Admin_ sidebar, go to **Customers** > **Customer Groups**.

1. Open the record in edit mode.

1. Make the necessary changes.

1. When complete, click <span class="btn">Save Customer Group</span>.

## To assign a customer to a different group:

1. On the _Admin_ sidebar, go to **Customers** > **All Customers**.

1. Find the customer in the list and select the checkbox in the first column.

    - Set the **Actions** control to `Assign a Customer Group`.

    - Set the **Group** control to the new group.

    - When prompted to confirm, click <span class="btn">OK</span>.

      ![]({% link images/images/stores-customer-group-assign.png %}){: .zoom}
      _Assign a Customer Group_

## To delete a customer group

<!--{% if "Default.B2B Only" contains site.edition %}-->
A customer group that is associated with a [shared catalog]({% link catalog/catalog-shared.md %}) cannot be deleted.

<!--{% endif %}-->
1. On the _Admin_ sidebar, go to **Customers** > **Customer Groups**.

1. Open the record in edit mode.

1. In the button bar, click **Delete Customer Group**.

1. When prompted to confirm, click <span class="btn">OK</span>.

1. When complete, click <span class="btn">Save Customer Group</span>.
