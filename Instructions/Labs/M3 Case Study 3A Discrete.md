---
lab:
    title: 'Case study 3A Discrete manufacturing'
    module: 'Module 3 Implement production methods'
---

# Module 3 Implement production methods

## Case study 1B Discrete manufacturing

### Exercise #1: Create a production order

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

### Exercise #2: Start a discrete production order (Bonus)

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

### Exercise #3: Run a resource schedule

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

3. Select **Delete**.

    > **Note** A message box will appear to confirm
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

### Exercise #4: Configure manufacturing execution (Bonus)

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


### Exercise #5: Configure automatic route consumption on setup jobs (Bonus)

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

### Exercise #6: Use manufacturing execution (Bonus)

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

9. Set the **Use timecard** toggle to **Yes**.

10. In the **Configuration** field, enter or select **Production**.

11. Set the **Supervisor options** toggle to **Yes**.

12. Select **OK**.

13. In the list, select **Shannon Dascher** to view the **Employees
    details** page.

14. Select the **Time registration** tab.

15. Select **Edit**.

16. In the **Badge ID** field, enter or select **069**.

17. Select **Save**.

18. Close the page.

19. Go to **Production control \> Manufacturing execution \> Job card
    device**.

20. In the **Personnel number** field, enter or select **069**.

21. Select **Log in**.

22. Select **Start job**.

23. Set **Quantity to start** to **1.00**.

24. Select **OK**.

25. Select **Report progress**.

26. Set **Error quantity** to **1.00**.

27. In the **Error cause** field, select **Material**.

28. Select **Complete**.

29. Select **Break**.

30. In the list, select **break from work.**

31. Select **OK**.

32. Select **Stop break**.

33. Select **Activity**.

34. In the list, find and select **Equipment repair**

35. Select **OK**.

    >**Note** A message may appear stating, "You are currently registered on other jobs(s). You need to report feedback on these before commencing on new jobs.''
  
36. Select **OK**.

37. Set **Error quantity** to **2.00**.

38. In the **Error cause** field, enter **Machine**.

39. In the **Job status** field, select **Stopped**.

40. Select **Complete**.

41. Select **Next job**.

42. Select **Previous job**.

43. Select **Report progress**.

44. Set **Good quantity** to **5.00**.

45. In the **Job status** field, enter **Completed**.

46. Select **Complete**.

47. Close the page.

### Exercise #7: Create an approved vendor list and setting method to Warning Only (Bonus)

Contoso Orange Juice USP2 has determined that approved vendor control
shall be placed on item M7001 with the approved vendor being US-113, and
they have assigned the task to you

Can you perform this task?

You will have to do the following:

- Set up the approved vendor or default vendor

- Set vendor check method to Warning Only

#### Steps

**Set up the approved vendor or default vendor**

1. In **USP2** (Navigate to upper right corner of window and change
    company from USMF to USP2), Go to **Product information management
    \> Products \> Released products**.

2. Use the Quick Filter to filter on the **Item number** field with a
    value of **M7001**.

3. In the list, select the item number **M7001** to view the **Released
    product details** page.

4. On the Action Pane, select **Purchase**.

5. In Approved vendor group, select **Setup**.

6. Select **Add**.

7. In the **Vendor** field, enter or select **US-113**.

8. Select **Save**.

9. Close the page.

**Set the vendor check method to Warning Only**

1. On the **Released product details** page, select **Edit**.

2. Expand the **Purchase** FastTab, set the **Approved vendor check
    method** field from **No check** to **Warning only**.

3. Select **Save**.

4. **Close** the page.





