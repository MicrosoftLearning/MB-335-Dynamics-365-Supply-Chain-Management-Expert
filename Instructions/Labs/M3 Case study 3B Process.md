---
lab:
    title: 'Case study 3B Process manufacturing'
    module: 'Module 3 Implement production methods'
---

# Module 3 Implement production methods

## Case study 3B Process manufacturing

### Exercise #1: Create and associate a batch attribute

Company USPI has a new requirement for part P4000, polypropylene
pellets, to test and record the melting point for each batch is needed.

The product definition employee wants to create a batch attribute for
the melting point as an integer attribute with a min of 0 and max of 500

The item specific requirements are 130 -- 171° C. Customer\
US-024 requires a melting point of 135 -- 165° C for use in their
manufacturing processes.

The product definition employee wants to associate the batch attribute
with the item and the customer with the correct attribute ranges

You were called to help. Can you help the product definition employee?

You will have to do the following:

- Create a new batch attribute

- Set the attribute minimum and maximum

- Associate the batch attribute with\
    the item

- Set the item attribute minimum and maximum

- Assign financial dimensions to the item

- Associate the batch attribute with the customer

- Set the customer attribute minimum and maximum

#### Steps

**Create a new batch attribute**

1. In **USPI** company go to **Inventory Management** \> **Setup** \>
    **Batch** \> **Batch attributes**.

2. Select **New**.

3. In the **Attribute** field, enter or select **MeltingPoint**.

4. In the **Description** field, enter or select **Melting Point (C)**.

5. In the **Attribute type** field, select **Integer**.

**Set the attribute minimum and maximum**

1. In the **Minimum** field, enter or select **0**.

2. In the **Maximum** field, enter or select **500**.

3. In the **Increment** field, enter or select **1**.

4. Select **Save**.

5. Close the page.

**Associate the batch attribute with the item**

1. Go to **Product Information management \> Products \> Released
    products**.

2. Use the Quick Filter to filter on the Item number field with a value
    of **p4000**.

3. On the **Manage Inventory** tab, in the **Batch Attributes** group,
    select **Product specific**.

4. Select **New**.

5. In the Attribute relation field, select **Melting Point**.

**Set the item attribute minimum and maximum**

1. In the **Tolerance action** field, select **Not allowed**.

2. Set **Minimum** to **130**.

3. Set **Maximum** to **171**.

4. In the **Target** field, enter or select **150**.

5. Select **Save**.

6. Close the page.

**Assign the default financial dimension to the item**

1. Go to **Product Information management \> Products \> Released
    products**.

2. Use the **Quick Filter** to filter on the **Item number** field with
    a value of **M2005**.

3. Select the link for M2005 to go to the details page.

4. Select **Edit**.

5. Expand **Financial dimensions** fasttab, select **OJ B2B** for the
    **ProductGroup** financial dimension.

6. Select **Save**.

7. Close all pages.

**Associate the batch attribute with the customer**

1. Go to **Product Information management \> Products \> Released
    products**.

2. Use the Quick Filter to filter on the Item number field with a value
    of **p4000**.

3. Select **Customer specific** in the Batch Attributes group on the
    **Manage Inventory** tab.

4. Select **New**.

5. In the **Attribute relation** field, enter or select **Melting
    Point**.

6. In the **Account selection** field, enter or select **US-024**.

**Set the customer attribute minimum and maximum**

1. Set **Minimum** to **135**.

2. Set **Maximum** to **165**.

3. Select Save.

4. Close the page.

### Exercise #2: Create a new batch number and manually record the batch attribute

The inventory manager for company USPI wants to create a new batch
number for part P4000.

He is not sure where to start or what to do.

Can you help?

You will have to do the following:

- Create a new batch number

- Manually record the batch attribute data

#### Steps

**Create a new batch number**

1. Go to **Warehouse management \> Setup \> Inventory \> Batches**.

2. Select **New**.

3. In the **Batch number** field, enter or select **GTL0001**.

4. In the **Item number** field, enter or select **P4000**.

5. In the **Manufacturing date** field, enter today's date.

6. Select **Save**.

**Manually record the batch attribute data**

1. On the Action Pane, select **View**.

2. Select **Inventory batch attributes**.

3. Select **New** then select Attribute dropdown icon and select
    **MeltingPoint**. Select **Load item attributes**.

4. In the **Attribute value** field, enter or select **163**.

5. Select **Save**.

6. Close all pages.

### Exercise #3: Create quality orders and verify batch attributes

At company USPI, item M2005 is set to have a quality order created upon
the purchase order product receipt.

They would like to:

create a new PO for 500 pounds of material, receive the material, and
enter the information in the quality order that is created.

Verify that the batch attribute data was updated upon completion of the
quality order

They are not sure how to perform this transaction and asked for your
help.

Can you help?

You will have to do the following:

- Create a new purchase order for item M2005

- Receive the purchase order

- Complete the quality order

- Verify the batch attribute data

#### Steps

**Create a new purchase order**

1. Go to **Procurement and sourcing \> Purchase orders \> All purchase
    orders.**

2. Select **New**.

3. In the **Vendor account** field, enter or select **US-102**.

4. Select **OK**.

5. In the **Item number** field, enter or select **m2005**.

6. Set **Quantity** to **500**.

7. Set the **Unit** price to **6.99**.

8. Select **Save**.

9. On the Action Pane, select **Purchase**.

10. In the **Actions** group, select **Confirm**.

11. Notate the purchase order number.

12. Close the page.

**Receive the purchase order**

1. Go to **Inventory management \> Inbound orders \> Arrival
    overview**.

2. Expand **Arrival query details**.

3. Set the value of **Restrict to site** to **1**.

4. Select **Update**.

5. In the **Arrival overview profile name** field, enter or select
    **Inquiry** to view the purchase order in the Receipts grid.

6. Select **Update**.

7. Search for the purchase order created and select the record.

8. Select **Start arrival** in the **Receipts** FastTab. This will
    update the status on in the Receipt in progress field to Complete.

9. Re-select your PO.

10. Select **Journals**.

11. Select **Show arrivals from lines**.

12. Select **Inventory**.

13. Select **Display dimensions**.

14. Select the **Site** check box.

15. Select the **Warehouse** check box.

16. Select the **Batch number** check box.

17. Select **OK**.

18. Right select and view details on the **Batch number** field.

19. Select **New**.

20. In the **Batch number** field, enter or select **GTLB001**.

21. Expand **Properties** Fast Tab and enter in the **Manufacturing
    date** field.

22. Select **Save**.

23. Close the page.

24. Close the **Batches** page.

25. In the **Batch number** field, enter or select the batch that was
    created (GTLB001).

26. Select **Post**.

27. Select **OK**.

28. Select **Functions**.

29. Select **Product receipt**.

30. In the **Product receipt** field, enter or select 2.

31. Select **OK**.

32. Close the page.

**Complete the quality order**

1. Go to **Inventory Management \> Periodic tasks \> Quality Management
    \> Quality orders**.

2. Select **Results.**

3. Select **Edit**.

4. Set Result quantity to **5**.**89**.

5. Set Result value to **15.4**.

6. Select **Save**.

7. Close the page.

8. Select **Validate**.

9. In the **Validate 0d by** field, enter or select Julia Funderburk.

10. Select **OK**.

**Verify the batch attribute data**

1. Select the **Inventory dimensions** tab.

2. Select to follow the link in the **Batch number** field.

3. On the Action Pane, select **View**.

4. Select **Inventory batch attributes**.

5. Close the page.

### Exercise #4: Complete a batch reservation using an attribute requirement

At company USPI, part P5000 is set up with internal requirements for
batch attributes.

The operations manager wants to enter the batch order, manufacture the
material, and record the test results.

Then the shipping operator will use the batch reservation form to
reserve a batch based upon the customer testing requirements

They both know that a new customer requirement for customer US-026 must
be created.

A new batch order of 500,000 pounds of material shall be created to meet
the requirements of a sales order from customer US-026.

They called you as the MFG functional consultant to help them achieve
this. Can you help?

You will have to do the following:

- Create a customer attribute requirement

- Create a new batch order

- Process the batch order

- Complete the quality order

- Create a sales order

- Complete the batch reservation and shipment

#### Steps

**Create a customer attribute requirement**

1. In **USPI** go to **Product information management** \> **Products**
    \> **Released products**.

2. Use the Quick Filter to filter on the **Item number** field with a
    value of **p5000**.

3. Select **Customer specific** from the **Manage Inventory** tab.

4. Select **New**.

5. In the **Attribute relation** field, enter or select
    **VolatilePct**.

6. In the **Account selection** field, enter or select **us-026**.

7. Set **Minimum** to **98**.

8. Select Save.

9. Close the page.

**Create a new batch order**

1. In **USPI** company go to **Production Control** \> **Production
    Orders** \> **All Production orders**.

2. Select **New batch order**.

3. In the **Item number** field, enter or select **p5000**.

4. In the **Delivery** field, enter a date.

5. Select **Create**.

**Process the batch order**

1. On the Action Pane, select **Production order**.

2. Select **Estimate**.

3. Select **OK**.

4. Select **Start**.

5. Select **OK**.

6. On the Action Pane, select **View**.

7. Select **Picking list**.

8. In the list, select the link in the selected row.

9. In the journal lines, select each row and complete the batch
    reservation.

10. Select **Inventory**.

11. Select **Reservation**.

12. Select **Reserve lot**.

13. Close the page.

14. Select **Post**.

15. Select **OK**.

16. Close the page.

17. Close the page.

18. On the Action Pane, select **Production order**.

19. Select **Report as finished**.

20. Select **OK**.

**Complete the quality order**

1. On the Action Pane, select **View**.

2. Select **Quality orders**.

3. Select **Results**.

4. Select **Edit**.

5. Set Result quantity to **5000**.

6. Set Test result to **98.5**.

7. Select **Save**.

8. Close the page.

9. Select **Validate**.

10. In the **Validated by** field, enter or select a value.

11. Select **OK**.

12. Close the page.

**Create a sales order**

1. Go to **All sales orders**.

2. Select **New**.

3. In the **Customer account** field, enter or select **us-026**.

4. Select OK.

5. In the **Item number** field, enter or select **p5000**.

6. Set **Quantity** to **500000**.

7. Select **Save**.

**Complete the batch reservation and shipment**

1. Select **Inventory**.

2. Select **Batch reservation**.

3. Select **Batch attribute search**.

4. Select **Customer attributes**.

5. Select **OK**.

6. Select **Reserve lot**.

7. Refresh the page.

8. Close the page.

9. Select **Post packing slip**.

10. Select **OK**.

11. Close the page.


### Exercise #5: Create a batch attribute for a potency item

At company USPI, part number M2004, ETDA, must be designated a
potency-controlled item for the Acidity batch attribute.

The target value for Acidity should be 1.7. Set up the batch attribute,
assign it to the product, and designate the product as a potency item.

The product manager is not sure how to configure the system to do that.

You were called as the MFG functional consultant to help.

Can you help?

You will have to do the following:

- Create a batch attribute

- Assign the attribute to\
    the item

- Assign potency information

#### Steps

**Create a batch attribute**

1. Go to **Inventory management** \> **Setup** \> **Batch** \> **Batch
    attributes**.

2. Select **New**.

3. In the **Attribute** field, enter or select **Acidity**.

4. In the **Description** field, enter or select **Acidity**.

5. In the **Attribute** **Type** enter or select field, select
    **Fraction**.

6. In the **Maximum** field, enter or select **10**.

7. In the **Increment** field, enter or select 0**.01**.

8. Select **Save**.

9. Close the page.

**Assign the attribute to the item**

1. Go to **Product information management** \> **Products** \>
    **Released products**.

2. Use the Quick Filter to filter on the **Item number** field with a
    value of **M2004**.

3. On the Action Pane, select **Manage inventory**.

4. Select **Product specific**.

5. Select **New**.

6. In the **Attribute relation** field, select **Acidity**.

7. Set **Minimum** to **1**.

8. Set **Maximum** to **3**.

9. In the **Target** field, enter or select **1.7**.

10. Select **Save**.

11. Close the page.

**Assign potency information**

1. Select M2004 product on the Release product details page.

2. Select **Edit**.

3. Select **Save**.

    >**Note** In case if Base attribute column is not visible select three
    dots and select Insert columns. Search for b and select Base
    attribute.

4. Select **Update**.

5. In the **Base attribute** field, enter or select **Acidity**.

6. Select **Save**.

### Exercise #6: Modify and activate a copy of a potency item formula

At company USPI, were reviewing all their items and they found out that
part M2004 has been determined to be a potency-controlled item.

The formula for item P2000 needs to be adjusted to set M2004 as an
active potency item.

The formula for P2000 should be modified to indicate the change, and
item M2007 should be set as a compensating material for part M2004 with
a compensation factor of 1

They are not sure how to reflect this in the system and they called you
to help.

Can you help?

You will have to do the following:

- Copy the formula for item P2000

- Modify the M2004 and\
    M2007 lines

- Approve and activate the formula

#### Steps

**Copy the formula for item P2000**

1. Go to **Product information management** \> **Products** \>
    **Released products**.

2. Use the Quick Filter to filter on the **Item number field** with a
    value of **\'p2000\'**.

3. On the Action Pane, select **Engineer**.

4. Select **Formula versions**.

5. Select **New**.

6. Select **Formula and formula version**.

7. In the Number field, enter **001** and in the **Name** field, enter
    or select **Formula123**.

8. Select **Yes** in the **Copy** field.

9. In the **Site** field, enter or select 1.

10. Select **OK**.

11. In the **Formula version** field, Enter 2000 and select for P2000
    from the drop-down.

12. Select **OK**.

**Modify the M2004 and M2007 lines**

1. In the list, select row M2004.

2. In the Ingredient type enter or select field, select **\'Active\'**.

3. In the list, select row M2007.

4. In the Ingredient enter or select field, select
    **\'Compensating\'**.

5. Select **Save**.

6. Select **Ingredients**.

7. Select **Compensation principle**.

8. In the Active ingredient field, select **M2004**.

9. Select **OK**.

10. Close the page.

**Approve and activate the formula**

1. In the list, select the old formula version.

2. In the **To date** field, Enter current date

3. In the list, select the new formula version.

4. In the **From date** field, enter current date and select Formula
    version tab on the Action pane.

5. Select **Approval.**

6. In the **Approved by** field, select Glen John.

7. Select **Select**.

8. Select **Yes** in the **Do you also want to approve the formula?**
    field.

9. Select **OK**.

10. Select **Activate**.

### Exercise #7: Set up pricing based on an item's attribute (Bonus)

At company USPI, part M2004 has been determined to be a
potency-controlled item.

The pricing of part M2004 shall be based upon the acidity level, where
the ratio of the actual acidity level against the target is multiplied
by the based price of \$4.70 and a constant of 1.5 to determine the
purchase price of the batch.

the purchase agent, want to setup the pricing for\
the item and couldn't.

The support team asked you to help the purchase agent.

Can you help?

You will have to do the following:

- Create an attribute pricing expression

- Complete and post the trade agreement

####  Steps

**Create an attribute pricing expression**

1. Go to **Procurement and sourcing** \> **Setup** \> **Prices and
    discounts** \> **Attribute-based pricing details**.

2. Select **New**.

3. In the **Name** field, enter or select Pricing.

4. In the **Description** field, enter or select Pricing expression.

5. Select **Add variable**.

6. In the **Equation element type** field, select **Unit price**.

7. Select **Add variable**.

8. In the **Equation element type** field, select **Constant**.

9. Set **Constant** to **1.5**.

10. Select **Add variable**.

11. In the **Equation element type** field, select **Batch attribute -
    Target**.

12. In the **Attribute** field, select **Acidity**.

13. Select **Add variable**.

14. In the **Equation element type** field, select **Batch attribute -
    Actual**.

15. In the **Attribute** field, select Acidity.

16. In the **Equation** field, enter or select (A/B)\*(D/C).

17. Select **Validate equation**.

18. Close the page.

**Complete and post trade agreement**

1. Go to **Product information management** \> **Products** \>
    **Released products**.

2. Use the Quick Filter to filter on the **Item number** field with a
    value of **m2004**.

3. On the Action Pane, select **Purchase**.

4. Select **Create trade agreements**.

5. Select **Edit**.

6. In the **Name** field, select **Price**.

7. Select **Lines**.

8. In the **Item relation** field, enter or select **M2004**.

9. In the **Site** field, enter or select **1**.

10. In the **Warehouse** field, enter or select **11**.

11. Set **Amount in currency** to **4.7**.

12. In the **Attribute-based pricing ID** field, enter the pricing ID
    USPI-00001.

13. Select **Save**.

14. Select **Post**.

15. Select **OK**.

16. Close the page.

### Exercise #8: Record a potency attribute upon receipt (Bonus)

A new batch of item M2004 is to be purchased into inventory and
received, with the batch attribute result being entered upon receipt.

You were asked to review the pricing of M2004 to verify that the
calculation meets the requirements of the attribute-based pricing

Can you perform this task?

You will have to do the following:

- Batch Number Creation

- Create a purchase order for item M2004

- Receive and enter a batch attribute value

- Invoice and review pricing

#### Steps

**Create a purchase order**

1. Perform the below steps in USPI. Go to **Procurement and sourcing**
    \> **Purchase orders** \> **All purchase orders**.

2. Select **New**.

3. In the **Vendor account** field, enter or select US-102.

4. In the **Warehouse** field, select **13**.

5. Select **OK**.

6. In the **Item number** field, enter or select **m2004**.

7. Set **Quantity** to **800**.

8. On the line details FastTab, under Financial dimensions tab, Update
    the productGroup as **OJB2B**

9. On the Action Pane, select **Purchase**.

10. Select **Confirm**.

**Receive and enter a batch attribute value**

1. On the Action Pane, select **Receive**.

2. Select **Product receipt**.

3. In the **Product receipt** field, enter or select 1234

4. Select **Update line**.

5. Select **Registration**.

6. Select **Add registration line**.

7. Select **Confirm registration**.

8. Select **Save**.

9. Close the page twice until you reach the page where you are posting
    product receipt order page.

**Invoice and review pricing**

1. In the **Quantity** field, select **Registered quantity**.

2. Select **OK**.

    > **Note** If you get an error message while posting the order stating
    "Blank is not allowed in the ProductGroup field for the
    combination." Please follow the below steps.

3. Navigate to **General Ledger \> Chart of Account \> Structures \>
    Configure account structures**.

4. Search for **Manufacturing PI P&L**

5. Make sure for the main accounts, the "Blank values are allowed"
    option is checked

6. Select on **Activate** from the Action pane

7. Select on **Activate**

    > **Note** Once the above steps are completed, please perform steps from "Receive and enter a batch attribute value to post the order".

8. On the Action Pane, select **Invoice**.

9. Select **Invoice**.

10. In the **Number** field, enter **123**

11. In the **Invoice date** field, enter current date.

12. Select **Update match status**.

13. Select **Post**.

14. On the Purchase order lines . Select **Inventory**.

15. Select **Transactions**.

### Exercise #9: Reporting and balancing batch orders (Bonus)

A new batch order is to be created for part P2000, including reserving
batches of the active ingredients, performing batch balancing, and
posting the picking list.

The production manager wants to create a production order and process
the order for a new batch of part P2000

The production manager is new to the system and wants you help.

Can you help?

You will have to do the following:

- Configuring Working time calendar

- Create a batch order for part P2000 and process the batch order
    through Start

- Complete batch reservation and balancing for active ingredients

- Post the picking list and report as a finished batch order

#### Steps

Configuring Working time calendar

1. Go to **Production Control \> Setup \> Calendars\> Calendars**.

2. Select **24hr** and select **Working times.**

3. Select **Compose working times.**

4. In **To date** field, enter date.

5. In **Working time template** field, select **24hr**. Select **OK**.

6. Close the page once the operation is completed.

7. Close it again till you reach Working time calendars page.

8. Select **8hr** and select **Working times**.

9. Select **Compose working times**.

10. In **Working time template** field enter **8Hr**. Select **OK**.

**Create a batch order for part P2000 and process the batch order
through Start**

1. Go to **Production control** \> **Production orders** \> **All
    production orders**.

2. Select **New batch order**.

3. In the **Item number** field, enter or select **p2000**.

4. Select **Create**.

5. On the Action Pane, select **Production order**.

6. Select **Estimate**.

7. Select **OK**.

8. Select **Start**.

9. Select **OK**.

**Complete Batch Reservation and Balancing for active ingredients**

1. Select **Batch balancing** under Process \> Production Order from
    the Action pane

2. In the list, select **M2004**, **M2002** and **M2005**

    > **Note** If you do not see the Batch lines present for M2002 and
M2005. Proceed with creating a Purchase orders for M2002 and M2005.

3. Select the **Marked** check box respectively for all the three items

4. Select **Balance batch ingredients**.

5. Select **Confirm the formula**.

6. Select **OK**.

**Post the picking list and report as a finished batch order**

1. On the Action Pane, select **View**.

2. Select **Picking list**.

3. In the list, select the link for the picking list.

4. Select **Post**.

5. Select **OK**.

6. Close the page.

7. On the Action Pane, select **Production order**.

8. Select **Report as finished**.

9. Select a value in **Batch number** field and then select on the same
    batch number

10. Select **New**.

11. In the **Batch number** field, enter or select a value.

12. In the **Manufacturing date** field, enter a date.

13. Select **Save**.

14. Close the page.

15. In the **Batch number** field, select the created batch number.

16. Select **OK**.