---
lab:
    title: 'Case study 1A Discrete, Process and Lean manufacturing features'
    module: 'Module 2 Configure production prerequisites'
---

# Module 2 Configure production prerequisites

## Case study 1A Discrete, Process and Lean manufacturing features

### Exercise #1: Update the production control parameters

When you are starting to use the Production control module, you are
required to do some configurations that will help the system operate
according to your design and process design

The Operations manager at USMF,  wants to make some changes to the
policies so everything runs more efficiently. He wants to be
sure routes are not allowed to be modified or have
their approvals removed. In order to accomplish this, a new route
operation should be created, and the effective dates updated.

Can you help the operation manager to perform this?

You will have to do the following:

- Update the production control parameters

#### Steps

1. Go to **Production control \> Setup \> Production control
    parameters**.

2. Set the **Block removal of approval** slider to **Yes** under
    the **Routes** group.

3. Set the **Block editing** slider to **Yes** under
    the **Routes** group.

4. Select **Save**.

5. **Close** all pages.

### Exercise #2: Create new production pools

USMF has been getting reports from the customers that orders are not
arriving on time and that some of the delivered orders are missing
pieces. One of the supervisor wants you to determine what is causing
these problems so the company can find a solution.

You decide that you want more visibility into production orders that are
delayed, and you want to track subcontracted production orders that are
missing deliveries, production orders with missing materials and orders
that are delayed due to machine failures.

How would you perform this?

You will have to do the following:

- Production pool for Delayed sub contracted work

- Production pool for missing materials

- Production pool for machine failures

#### Steps

**Create a production pool for delayed subcontracted work**

1. Open **Production control \> Setup \> Production \> Production
    pools**.

2. Select **New** to create a new pool.

3. Enter or select **Delay-Sub** in the **Pool** field.

4. Enter or select **Subcontracted Work Delayed** in the **Name**
    field.

**Create a production pool for missing materials**

1. Select **New** to create a new pool.

2. Enter or select **MATMISSING** in the **Pool** field.

3. Enter or select **Materials Missing** in the **Name** field.

**Create a production pool for machine failures**

1. Select **New** to create a new pool.

2. Enter or select **MACHFAIL** in the **Pool** field.

3. Enter or select **Machine Failure** in the **Name** field.

4. Select **Save**.

5. Close all pages.

### Exercise #3: Create and manage resources

Company USMF has bought a new packing robot that will reduce the need
for manual labor in the speaker packing workshop.

Workers from this group can therefore be reassigned to perform other
work as the new robot becomes fully operational.

You were asked to add the robot as a resource

How would you perform this?

You will have to do the following:

- Create capabilities

- Assign resource to capabilities

- Assign capabilities to a resource

#### Steps

**Create capabilities**

1. Go to **Organization administration \> Resources \> Resource
    capabilities**.

2. Select **New** from the Navigation bar.

3. Enter or select **GTL-Assembly** in the **Capability** field and
    **Assembly** in the **Description** field.

4. Select **New**.

5. Enter or select **GTL-Packing** in the **Capability** field and
    **Packing** in the **Description** field.

6. Close the **Resource capabilities** page.

**Assign resources to capability**

1. Go to **Organization administration \> Resources \> Resource
    capabilities**.

2. Select **GTL-Assembly** from the list of capabilities.

3. Select **Add** from the toolbar.

4. Select **5110**, Assembly worker 1, in the **Resource** field.

5. Accept the default **Expiration** date of **Never**.

6. Enter or select **1** in the **Priority** field.

7. Accept the default **Level** of 0.00.

8. Repeat steps 3 to 7, for the resource 5111 [and click Save]{.mark}.

9. Close the **Resource capabilities** page.

**Assign capabilities to a resource**

1. Go to **Organization administration \> Resources \> Resources**.

2. Select resource 5111 in the grid.

3. Expand the **Capabilities** FastTab.

4. Select **View \> All** from the toolbar.

5. Select **Add** from the toolbar.

6. Enter or select GTL-Packing in the **Capability** field.

7. Accept the default **Effective** date of today\'s date.

8. Accept the default **Expiration** date of **Never**.

9. Accept the default **Level** of 0.00.

10. Enter or select **2** in the **Priority** field

11. Close the **Resources** page.

### Exercise #4: Create an operation, assign relations and create a route

The company you are consulting has decided to produce a series
of ebooks for a client.

The production manager at **USMF**, wants to create an operation for the
finished good, assign relations, and create a route

Can you help the production manager?

You will have to do the following:

- Create and configure an operation

#### Steps

1. Go to **Production control \> Operations \> All routes**.

2. Select **New**.

3. In the **Name** field, enter or select **eBook route**.

4. In the **Item group** field, enter or select **TV&Video**.

5. Select **Save**.

6. Select **Route** on the Action Pane then in the **Maintain** group,
    select **Route details**.

7. Select **New**.

8. In the **Operation** field, enter or select **Assembly**.

9. In the Scrap Percentage field, enter **20**.

10. In the **Link type** field, select **Soft**.

11. Select **New**.

12. In the **Oper. No.** field, enter **20**.

13. In the **Operation** field, enter or select **Padding**.

14. In the Scrap percentage field, enter **30**.

15. In the **Link type** field, select **Hard**.

16. Select **New**.

17. In the **Oper. No**. field, enter **30**.

18. In the **Priority** field, select **Primary**.

19. In the **Operation** field, enter or select **Packing**.

20. Refresh the page.

21. Select **Save**.

22. **Close** all pages.

- \[!NOTE\] The message bar may appear with a message that states,
    > \"There exist no relation for operation Padding.\" The route
    > contains the order of operations and the assignment of operations
    > will occur in the next steps.

23. Go to **Production control \> Setup \> Routes \> Operations**.

24. Select **New**.

25. In the **Operation** field, enter or select **eBook**.

26. In the **Name** field, enter or select **eBook assembly**.

27. Select **Relations**.

28. Select **New**.

29. In the **Route group** field, enter or select **Discrete**.

30. Expand the **Setup** section.

31. In the **Formula** field, select **Capacity**.

32. In the **Costing resource** field, enter or select **1211**. A
    dialogue box appears informing that the default time and cost values
    from the costing resource will be inserted. Select **Yes** to
    continue.

33. In the **Route relation** field, enter or select **eBook route**
    created in previous steps and **Route code** should be set to
    **Route**.

34. Select **Save**.

35. Close all pages.

### Exercise #5: Create a simple BOM without a version

You have been asked to assist the product designer at USMF and show her
how to create a simple BOM for a new light cabinet.

You will approve the BOM using employee 000020, Julia Funderburk.

You will use the parameters on the right

- Name: Light Cabinet

- Item group: Audio

- Site: 1pa

- Item:

- M0005 Enclosure

- M0006 Binding posts

- P0002 Speaker Damping Foam

- Quantity for each item: 1

You will have to do the following:

- Create a simple BOM

#### Steps

1. Go to **Product information management \> Bills of materials and
    formulas \> Bills of materials**.

2. Select **New**.

3. In the **Name** field, enter or select **Light Cabinet**.

4. In the **Site** field, enter or select **1**.

5. In the **Item group** field, enter or select **Audio**.

6. Select **Save**.

7. In the **Bill of materials lines** section, select **New**.

8. In the **Item number** field, enter or select **M0005**.

9. Select **New**.

10. In the **Item number** field, enter or select **M0006**.

11. Select **New**.

12. In the **Item number** field, enter or select **P0002**.

13. Select **Bill of materials** on the Action Pane then in the
    **Maintain** group, Select **Approval** and choose **000020, Julia
    Funderburk**.

14. Select **OK**.

15. Select **Save**.

16. Close all pages.

### Exercise #6: Create a BOM in the BOM designer (Bonus)

The new product designer at USMF has received a new specification for
the enclosure side of a cabinet.

She has requested your assistance.

You see that an item is not set up for this specification, so you only
need to create a simple BOM with component lines.

Use employee 000020, Julia Funderburk, to approve the BOM.

Create a BOM titled "High Quality Speaker" and assign it to the Audio
item group at site 1. Use the BOM designer to add items with warehouse
11 and the following quantities:

- 1 qty of M0008/High End Cabinet/Black

- 2 qty of M0002/Mid-Range Speaker Unit

- 1 qty of M0009/Protective Corners

You will have to do the following:

- Create a BOM in the BOM designer

#### Steps

1. Go to **Product information management** \> **Bills of materials and
    formulas** \> **Bills of materials**.

2. Select **New**.

3. In the **Name** field, enter or select **High Quality Speaker**.

4. In the **Site** field, enter or select **1**.

5. In the **Item group** field, enter or select **Audio**.

6. Select **Bill of materials** on the Action Pane then in the
    **Maintain** group, select **Designer**.

7. Select BOM **lines** on the Action Pane.

8. Select **Add to component BOM**.

9. In the list, find and select **M0008 / High End Cabinet / Black**.

10. Select **OK**.

11. Select BOM **lines**.

12. Select **Add after line.**

13. In the list, find and select **M0009 / Protective Corners**.

14. Select **OK**.

15. Select BOM **lines**.

16. Select **Add before line**.

17. In the list, find and select **M0002 / Mid-Range Speaker Unit**.

18. Select **OK**.

19. Close the **Designer** page.

20. Refresh the **Bill of materials** page. This will populate the
    previously created BOM formula lines.

21. In the list of Bill of materials lines, find and select the row for
    **M0002 / Mid-Range Speaker Unit**.

22. Set **Quantity** to **2.0000**.

23. In the Action pane, select **Approval** in the **Maintain** group in
    the **Bill of materials** tab.

24. Select **000020**, Julia Funderburk.

25. Select **OK**.

26. Close all pages.

### Exercise #7: Create a BOM with a version

The sales department has reported that there is a high demand for
rosewood colored speakers instead of the traditional black.

You are asked to prepare for the manufacture of more
rosewood colored speakers by creating a version, making a copy of
the existing BOM, removing item M0008/High End Cabinet/ Black
and add item M0008/High End Cabinet/Red for a quantity of 1.

Employee 000020, Julia Funderburk must approve the version.

Do not activate the BOM because the item is not ready for use yet.

Use the specifications given at right

- Item number: 72708

- Item name: High Quality Speaker Rosewood

- Item group: Audio

- Item model group: FIFO

- Storage Dimension group: SiteWH

- Tracking Dimension group: None

- Warehouse 11

- Approved by: 000020, Julia Funderburk

You will have to do the following:

- Create a BOM with a version

#### Steps

1. Go to **Product information management \> Products \> Released
    products.**

2. Select **New**.

3. In the **Product number** field, enter or select **72708**.

4. In the **Product name** field, enter or select **High Quality
    Speaker Red**.

5. In the **Item model group** field, enter or select **FIFO**.

6. In the **Item group** field, enter or select **Audio**.

7. In the **Storage dimension group** field, enter or select
    **SiteWH**.

8. In the **Tracking dimension group** field, enter or select **None**.

9. Select **OK**.

10. On the Action Pane, select **Manage inventory**.

11. Select **Default order settings**.

12. In the **Default order type** field, select **Production**.

13. Under the **Inventory** FastTab, In the **Default warehouse** field,
    enter or select **11**.

14. Close the page.

15. On the Action Pane, select **Engineer**.

16. Select **Designer**.

17. Select **BOM**.

18. Select **Create version**.

19. In the **Name** field, enter or select **High Quality Speaker
    Rosewood**.

20. Select **Yes** in the **Copy** field.

21. In the **Site** field, enter or select **1**.

22. Select **OK**.

23. In the **Item number** field, enter or select **D0004**.

24. Select **OK**.

25. In the tree, select **Item number: 72708\\M0008 / High End
    Cabinet**.

26. Select **BOM lines**.

27. Select **Delete**.

28. Select **BOM lines**.

29. Select **Add before line**.

30. In the list, find and select **M0008 / High End Cabinet /
    Rosewood**.

31. Select **OK**.

32. In the tree, select **Item number: 72708**.

33. Select **BOM**.

34. Select **BOM versions**.

35. Select **Approval**. Select **000020**, Julia Funderburk.

36. Select **Yes** in the **Do you also want to approve the bill of
    materials?** field.

37. Select **OK**.

38. Close all pages.

### Exercise #8: Create a production order

The minimum information required to create a production order is an
active bill of materials.

Create a new production order to test the previously created BOM

You will have to do the following:

- Create a new production order

#### Steps

1. Go to **Production control \> Production orders \> All production
    orders**.

2. Select **New production order**.

3. In the **Item number** field, enter or select **72708**.

4. In the **Site** field, enter or select 1.

5. Set **Quantity** to **10.00**.

6. In the **Time** field, enter **10:15 AM**.

7. Select **Create**.

8. Select the **Production order** tab in the Action Pane, then in the
    **Process** group, select **Estimate**.

9. Select **OK**.

10. Select **Release**.

11. Select **OK**.

12. Select **Start**.

13. Select **OK**.

14. Select **Report as finished**.

15. Select **OK**.

16. Select **End**.

17. Select **OK**.

18. Close all pages.

### Exercise #9: Start a discrete production order (Bonus)

You can get production orders either manually created or firmed from the
Master planning with status "Scheduled"

The production of the ash enclosure back sides of the speakers is ready
to be started.

The production supervisor wants to use the start form and select a
production order with status of "Scheduled" to start.

Can you help the production manager to perform this?

You will have to do the following:

- Start a discrete production order

#### Steps

1. Select **Production control \> Production orders \> All production
    orders**.

2. Select any production order with the production order status set to
    **Scheduled** (for example, P000191).

3. On the **Production order** action pane, select **Start**.

4. On the **Overview** tab, in the **Quantity** field, enter the
    quantity **2.00** of the production order to produce.

5. In the **Date** field, enter today's date for the date that the
    production starts.

6. Uncheck the **Start production** check box.

7. Select **OK**.

8. **Close** all pages.

### Exercise #10: Run a resource schedule

The Production Manager wants to use a newly purchased assembly robot to
increase flexibility in production.

In the past, when she designed the production process (route) for a
product, she had to specify where each operation was to be performed.

Now, she want to defer the allocation of where and by whom an operation
is performed until the production is scheduled, and to use excess
capacity in other workshops to eliminate bottlenecks in heavily loaded
workshops.

She is not sure how to do so and asked for your help.

Can you help?

You will have to do the following:

- Create capabilities and resources

- Identify the resources applicable for the operation

- Add requirements for a capability to an operation

#### Steps

**Create capabilities and resources**

1. Navigate to **Organization administration \> Resources \> Resource
    capabilities**.

2. Select **New**.

3. Enter or select **20** in the **Capability** field and **Assembly**
    in the **Description** field.

4. Select **New**.

5. Enter or select **30** in the **Capability** field and **Packing**
    in the **Description** field.

6. In the **Resources** FastTab, select **Add**.

7. Select **1222** (Speaker packing worker 1) in the **Resource**
    field.

8. Accept the default expiration date of **Never**.

9. Accept the default **Level** of 0.00.

10. Enter or select **1** in the **Priority** field.

11. Close the **Resource capabilities** form.

12. Open **Organization administration \> Resources \> Resources**.

13. Select **New**.

14. Enter or select **000727** in the **Resource** field.

15. Enter or select **Assembly robot** in the **Description** field.

16. Accept the default of **Machine** in the **Type** field.

17. In the **Capabilities** FastTab, select **Add**.

18. Select 20 in the **Capability** field.

19. Accept the default expiration date of **Never**.

20. Accept the default **Level** of 0.00.

21. Enter or select **1** in the **Priority** field.

22. Expand the **Resource groups** FastTab.

23. Select **View \> All**.

24. Select **Add**.

25. Enter or select **1210** in the **Resource group** field, enter or
    select the next working day in the **Effective** field, and then
    accept the default expiration date of **Never**.

26. Accept the default **Input warehouse**.

27. Accept the default **Input location**.

28. Scroll up, expand the **Calendars** tab, and select **Add**.

29. Select **24hr** in the **Calendar** field and then accept the
    default expiration date of **Never**.

30. Close the **Resources** form.

**Identify resources applicable for the operation**

1. Navigate to **Production control \> Operations \> All routes**

2. Select route **000002** (STANDARD SPEAKER - D0003) by selecting on
    the link for 000002.

3. Select the **Route** tab in the Action pane, then in the
    **Maintain** group, select **Route details**.

4. Verify operation 10 is selected in the top grid of the **Route**
    form.

5. In the bottom grid, select **Applicable Resources**.

6. Notice that all the resources from the 1210 resource group are
    listed.

7. Scroll one day forward by selecting the **Next day** button or
    choose the date picker field.

8. Select **OK**. This closes the **Applicable resources** form.

**To add requirements for a capability to an operation, follow these
steps:**

1. In the **Route details** form for route 000002, with operation 10
    selected in the top grid, select the **Resource requirements** tab
    on the bottom grid.

2. In the Resource requirements grid, select the line where
    **Requirement type** is **Capability** and **Requirement** is
    **Assembly**.

3. Select **Delete**. Note that a message box will appear to confirm
    the action. Choose **Yes** to delete the record.

4. Select **Maintain resource requirements.** This starts the wizard.

5. On the Welcome screen, select **Next**.

6. On the Search criteria screen, select **Capability** in the
    **Requirement type** field.

7. Enter or select **20** in the **Requirement** field.

8. Accept the default option for resource requirements on activity.

9. Select **Next**.

10. On the Action screen, leave the defaults and select Next.

11. On the New resource requirements screen, set **Requirement type** to
    **Capability**, **Requirement** to **20**, and check the **Operation
    scheduling** and **Job scheduling** check boxes.

12. Select **Next**.

13. On the summary screen, review your options and choose **Finish**.

14. Close all pages.

### Exercise #11: Configure costing policies

At USMF, you need to set profit-settings to help sales personnel
calculate an accurate sales price after considering all costs for
cabinet item D0002.

You should also be able to view the costing sheet to analyze the cost
breakdown

Can you help the sales personnel?

You will have to do the following:

- Update the profit settings on the item

- Review the costing sheet setup

- View the calculation details on the item

#### Steps

1. Go to **Product information management \> Products \> Released
    products**.

2. Use the **Quick Filter** to filter on the **Item number** field with
    a value of **D0002**.

3. In the list, select **D0002** to open the details page.

4. Expand the **Manage costs** FastTab.

5. Select **M9 cost group** to open the cost group details page.

6. Select **Edit**.

7. Set **Profit percentage** to **40.00**.

8. Select **Add**.

9. In the **Profit-setting** field, select **Profit 1**.

10. Set **Profit percentage** to **70.00**.

11. Select **Save**.

12. Close the page.

13. On the Action Pane, select the **Engineer** tab.

14. In the **BOM** group, select **BOM versions**.

15. Under the Bill of materials lines, select **M0005** to open the
    **Product information** dialog.

16. Select **M0005** item number (not product number) to open the
    **Released product details** page

17. Select Cost group **M2** in the **Manage costs** FastTab to open the
    **Cost group details** page.

18. Select **Edit**.

19. Set **Profit percentage** to **30.00**.

20. Select **Add**.

21. In the **Profit-setting** field, select **Profit 1**.

22. Set **Profit percentage** to **60.00.** Select Save.

23. Close the page.

24. Close all pages.

25. Go to **Cost management \> Indirect cost accounting policies setup
    \> Costing sheets**.

26. In the tree, select **Root\\Cost of Conversion\\COC-Material\\COC -
    M2 - Cabinets comp**.

27. Review the structure of the costing sheet.

28. In the tree, select **Root\\Cost of Conversion\\Overhead on
    Conversion\\COC - OVH4 - Labor overhead\\Indirect labor cost - Rate
    per process time**.

29. Review the **Absorption basis**, and **Rate** FastTabs values.

30. In the tree, select **Root\\Cost of Conversion\\Overhead on
    Conversion\\COC - OVH4 - Labor overhead**.

31. Select **OVH4**.

32. Set **Profit percentage** to **80.00**. Click on Save

33. Close all pages.

34. Go to **Product information management** \> **Products** \>
    **Released products**.

35. Use the **Quick Filter** to filter on the **Item number** field with
    a value of **D0002**.

36. Select the **D0002** link to open the **Released product details**
    page.

37. On the Action Pane, select the **Manage costs** tab.

38. In the **Set up** group, choose **Item price**.

39. Select the **Pending prices** tab.

40. Select **Calculate item cost**.

41. In the **Costing version** field, enter or select **10**.

42. Select **OK**.

43. Select **View calculation details**.

44. Select the **Costing sheet** tab.

45. Analyze the cost breakdown for the cabinet **D0002**.

46. Close all pages.

### Exercise #12: Configure manufacturing execution (Bonus)

The Production Manager determined that the best way to post picking
lists is to use the operation quantity feedback (backflush on
operations) method.

If the actual consumption on BOM items differs from the estimated
consumption, the employee can enter the actual item consumption when
providing quantity feedback

The production manager not sure how to perform this and asked for your
help.

Can you help?

You will have to do the following:

- Update the parameters under manufacturing execution production order
    default parameters

#### Steps

1. Open **Production control \> Setup \> Manufacturing execution \>
    Production order defaults**.

2. On the **Start** tab, select **Status** in the **Update start
    on-line** field.

3. In the **Automatic BOM consumption** field, select **Never**.

4. Select the **Operations** tab.

5. Set the **Setup** option to **No**.

6. In the **Automatic BOM consumption** field, select **Always**.

7. Select the **Report as finished** tab.

8. In the **Update finished report on-line** field, select
    **Quantity**.

9. In the **Automatic BOM consumption** field, select **Never**.

10. Close the **Production order defaults** form.

### Exercise #13 - Configure automatic route consumption on setup jobs (Bonus)

Your estimation on operation setup has proven accurate, so the
Production Manager decided that it is not necessary for employees to
register on setup jobs.

The time consumption on setup jobs must be posted automatically

How would you automate this posting?

You will have to do the following:

- Update routing groups.

- Update the routing group on the MES production order defaults

#### Steps

1. Open **Production control \> Setup \> Routes \> Route groups**.

2. From the list, select **Sfc Shop Floor Control Routing Group**.

3. Select **Edit**.

4. On the **General** FastTab, in the **Automatic route consumption**
    group, enable the **Setup time** field.

5. Close the **Route groups** form.

6. Open **Production control \> Setup \> Manufacturing execution \>
    Production order defaults**.

7. On the **Start** tab, in the **Automatic route consumption** field,
    select **Route group dependent**.

8. Enable the **Post route card now** field.

9. Close the **Production order defaults** form.

### Exercise #14: Use manufacturing execution (Bonus)

To proceed with testing the manufacturing execution, you need to enable
time registration for Shannon, the machine operator in USMF.

Shannon needs to use the job card terminal to control the execution of
the production order

Can you enable the time registration? How?

You will have to do the following:

- Enable time registration for the machine operator

#### Steps

1. Go to **Human resources \> Workers \> Employees**.

2. Use the **Quick Filter** to filter on the **Name** field with a
    value of **Shannon**.

3. Select **Activate on registration terminals** in the **Time** tab of
    the action pane.

4. In the **Calculation group** field, enter or select **Man**.

5. In the **Default calculation group** field, enter or select **Man**.

6. In the **Approval group** field, enter or select **AdmMan**.

7. In the **Standard profile** field, enter or select **Standard**.

8. In the **Profile group** field, enter or select **Man**.

9. Select **Yes** in the **Use timecard** field.

10. In the **Configuration** field, enter or select **Production**.

11. Select **Yes** in the **Supervisor options** field.

12. Select **OK**.

13. In the list, select **Shannon Dascher** to view the **Employees
    details** page.

14. Select the **Time registration** tab.

15. Select **Edit**.

16. .

17. In the **Badge ID** field, enter or select **069**.

18. Select **Save**.

19. Close the page.

20. Go to **Production control \> Manufacturing execution \> Job card
    device**.

21. In the **Personnel number** field, enter or select **069**.

22. Select **Log in**.

23. Select **Start job**.

24. Set **Quantity to start** to **1.00**.

25. Select **OK**.

26. Select **Report progress**.

27. Set **Error quantity** to **1.00**.

28. In the **Error cause** field, select **Material**.

29. Select **Complete**.

30. Select **Break**.

31. In the list, select **break from work.**

32. Select **OK**.

33. Select **Stop break**.

34. Select **Activity**.

35. In the list, find and select **Equipment repair**

36. Select **OK**.

37. Select **OK**.

38. Set **Error quantity** to **2.00**.

39. In the **Error cause** field, enter **Machine**.

40. Select **Complete**.

41. In the **Job status** field, select **Stopped**.

42. Select **Close**.

43. Select **Next job**.

44. Select **Previous job**.

45. Select **Report progress**.

46. Set **Good quantity** to **5.00**.

47. In the **Job status** field, enter **Completed**.

48. Select **Complete**.

49. Close the page.
