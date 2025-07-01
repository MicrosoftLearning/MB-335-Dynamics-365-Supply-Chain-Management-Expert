---
lab:
    title: 'Case study 3C Lean manufacturing'
    module: 'Module 3 Implement production methods'
---

# Module 3 Implement production methods

## Case study 3C Lean manufacturing

### Exercise #1: Create value streams

After defining and mapping the lean manufacturing value stream for USMF,
you are told to act as the value stream manager. You must create the
value stream within Microsoft Dynamics 365 Supply Chain Management

Can you do that?

You will have to do the following:

- Create a value stream

#### Steps

1. In **USMF** company go to **Production control \> Setup \> Lean
    production flow \> Value streams**.

2. Select **New** to create a new value stream.

3. Enter the following details for the new value stream:

4. Name: **SeaLeanVS**

5. Search Name: **SeaLean**

6. Manager: **Jodi Christiansen**

7. Select **Save**.

### Exercise #2 create a new production flow model

As the production (shop) floor supervisor at USMF, you have a logical grouping of work cell capacity with similar behavior
in capacity load for the work cells used to model the car speaker
production flow.

You must create a new production flow (SeaPFModel) to model the process
of painting the covers for the car speakers. The capacity and load of
the production flow will be measured in quantities of product that are
produced (Throughput).

The Cycle for this production flow will define 1 day as the number of
days used in automatic planning (i.e., EPE cycle is 1 day). The Add
method of Kanban scheduling will be used if there is no capacity
available during the required periods; the planning period type is Day
and the planning time fence is 10. To the right are more details you
will need for this task.

- Name: eBookProdFlow

- Description: eBook Production Flow

- Legal entity: USMF

- Value stream: SeaLeanVS

- Production group: 10

- Per cycle unit of measure: pcs

- Quantity per cycle: 1

- Average takt time: 1

- Minimum takt time: 1

- Maximum takt time: 2

- Period for actual cycle time (days): 1

You will have to do the following:

- Create a production flow model for SeaPFModel

- Create a production flow version for the USMF eBook production flow

- Set up the Takt and cycle times

#### Steps

**Create a production flow model**

1. Go to **Production control \> Setup \> Lean production flow \>
    Production flow models.**

2. Select **New**.

3. In the **Production flow model** field enter **SeaPFModel**.

4. In the **Model type** field enter **Throughput**.

5. In the **EPE Cycle in days** field enter **1**.

6. In the **Capacity shortage reaction** field enter **Add**.

7. In the **Planning period type** field enter **Day**.

8. In the **Planning time fence** field enter **10**.

9. In the **Capacity shortage reaction** drop down select **Postpone**.

10. Select **Save**.

**Create a production flow version**

1. Navigate to **Production control \> Setup \> Lean production flow \>
    Production flows**.

2. Select **New** on the action pane. A new production flow record is
    created.

3. In the **Name** field, enter **eBookProdFlow**.

4. In the **Description** field, enter **eBook Production Flow**.

5. In the **Legal entity** field, select **USMF**.

6. In the **Value stream** field, select **LeanProduction**.

7. In the **Production group** field, select **10**.

8. Select **Save**.

9. On the **Versions** FastTab, select **Add**.

10. Select **OK**.

**Set up the takt and cycle times**

1. Expand the **Versions** and **Version details** FastTabs.

2. In the **Per cycle unit of measure** field, select **pcs**.

3. In the **Quantity per cycle** field, enter **1**.

4. In the **Average takt time** field, enter **1**.

5. In the **Minimum takt time** field, enter **1**.

6. In the **Maximum takt time** field, enter **2**.

7. In the **Period for actual cycle time** (**days**) field, enter
    **1**.

8. Select **Save** in the action pane.

9. Ensure that the **Plan status** field for the version is set to **Draft**.

10. Close all forms.

### Exercise #3: Create a process activity

A new eBook stylus is being developed to compliment the eBook kits that
are sold at USMF.

The stylus is purchased from an outside vendor and configured at USMF.

A process activity is needed to configure the stylus and place it in
stock for use elsewhere.

Here are the details for the process activity:

- Name: Transfer Activity

- Process quantity: 10 pcs

- Operating unit: Lean Production

- Work cell: 1260

The company is not sure how to configure this and you were called as the
MFG functional consultant to help.

Can you help?

You will have to do the following:

- Create a process activity

#### Steps

1. Navigate to **Production Control \> Setup \> Lean Production Flows
    \> Production flows**.

2. Open the **Mid Range Speaker 2PF** production flow.

3. On the **Versions** FastTab, select the **Activities** button.

4. Select **Create new plan activity** button.

5. Select **Next**.

6. Enter **Transfer Activity** in the **Name** field.

7. Enter **10** in the **Process quantity** field.

8. In the **Unit** drop-down list, select **pcs**.

9. In the **Operating unit** drop-down list, select **LeanProduction**.

10. Select **Next**.

11. In the **Work cell** replenished drop-down list, select **1260**.

12. Set the **Update on hand on receipt** option to **Yes**.

13. Select **1260** in the **Replenishing** field.

14. Select **Finished product** in the **Product type** field.

15. Select **Next.**

16. Select Warehouse **13** in the **Transfer from location --
    warehouse** field.

17. Select location **13** in the **Transfer from location -- location**
    field.

18. For the transfer to location:

19. Select **22** in the **Warehouse** field.

20. Select location **01-01-2-1** in the **Location** field.

21. Select **Shipper** in the **Freighted by** field.

22. Select **Next.**

23. Select **Queue time after** record.

24. Enter **4** in **time** field.

25. Select **hr** in the **time unit** field.

26. Enter **10** in **per quantity** field.

27. Select the **Runtime** record.

28. Enter **2** in **time** field.

29. Select **hr** in **time unit** field.

30. Enter **10** in **per quantity** field.

31. Select **Next.**

32. Select **Finish.**

### Exercise #4 Create a new transfer activity

A new car speaker remote is being developed to complement the car
speaker kits sold at Contoso. The Standard speaker assembly production
flow needs to be amended to include a transfer activity to move the
configured remote to the Electrical Component warehouse

Details for production flow transfer activity are to the right

- Name: RemoteTransfer

- Process quantity: 10

- Operating unit: SeaLeanVS

- Replenishing resource group: 1250

- Update on hand on receipt: Yes

- Update on hand on pick: No

Transfer to warehouse ElComp, location Output

Freighted by shipper

- Runtime: 1 min per 25 pcs

You will have to do the following:

- Deactivate the current production flow version

- Create a new transfer activity

- Create the predecessor/successor relationship between the process
    and transfer activity with no constraints

#### Steps

**Deactivate the current production flow version**

1. Navigate to **Production Control \> Setup \> Lean production flow \>
    Production flows.**

2. Open the **Standard speaker assembly** production flow.

3. On the **Versions** FastTab, select Version **1**.

4. Select **Deactivate**.

5. Select **OK**.

**Create a new transfer activity**

1. On the **Versions** FastTab, select **Activities**. The **Production
    flow activities** form opens.

2. Select **Create new plan activity** in the action pane.

3. Select **Next**.

4. Enter **RemoteTransfer** in the **Name** field.

5. In the **Activity type** drop-down list, select **Transfer**.

6. Enter **10** in the **Process quantity** field.

7. In the **Unit** drop-down list, select **pcs**.

8. In the **Operating unit** drop-down list, select **SeaLeanVS**.

9. Select **Next**. The **Create process activity** and **Create
    Transfer Activity** page opens.

10. In the **Replenishing** drop-down list, select **1250**.

11. Set the **Update on hand on receipt** check box to **Yes**.

12. Set the **Update on hand on pick** check box to **No**.

13. In the **Product type** field, select **Finished product**.

14. Select **Next**. The **Assign picking activities** and **Assign
    transfer locations** page opens.

15. In the **Transfer to location** group, in the **Warehouse**
    drop-down list, select **11**.

16. In the **Location** drop-down list, select **11**.

17. In the **Freighted by** drop-down list, select **Shipper**.

18. Select **Next**. The **Assign** activity **time** page opens.

19. In the **Time** field for the **Runtime** row, enter **1**.

20. In the adjacent **Time unit** drop-down list, select **min**.

21. In the **Per quantity** field, enter **25**.

22. Select **Next**. The **Confirm selection** page opens.

23. Select **Finish**. The wizard closes, and a new production flow
    activity appears in the list.

24. Select **Save** in the action pane.

**Create the predecessor/successor relationship between the process and
transfer activity with no constraints**

1. Highlight the **Wiring Process** activity and, on the **Successor**
    tab, select the **Add successor** button.

2. Select the **Successor Activity** of **RemoteTransfer**.

3. For Cycle time ration, enter or select 1.

4. Select the **OK** button.

5. Close the **Production** flow activities form.

6. On the **Versions** tab, select the **Activate** menu button.

7. Select **OK**.

### Exercise #5: Add a successor to the production flow activity and perform validation and activation

The production Manager wants to revise Mid-Range Speaker 2 PF production
flow so that the Transfer_W12_to_W11 activity is succeeded by the
Process_Activity_1 activity.

Here are the details for production flow transfer activity relations:

- Constraint: 1 hour

- Cycle time ratio: 2

He is not quite sure how to do this revision and wants your help.

Can you help?

You will have to do the following:

- Add a successor to the production flow activity

- Perform validation and activation

#### Steps

**Add a successor to the production flow activity**

1. Navigate to **Production control** \> **Setup** \> **Lean production
    flow** \> **Production flows**.

2. Select the name of the Mid-Range Speaker 2 PF production flow.

3. On the **Versions** FastTab, select **Activities**.

4. In the list on the left, select the **00074 -- Transfer from
    Warehouse 13 to 51** activity.

5. On the **Successors** FastTab, select **Add successor**. The
    **Create activity relation** dialog opens.

6. In the **Successor** group, in the **Activity** drop-down list,
    select Activity **000086.**

7. Select the **Constraint** check box.

8. In the **Constraint value** field, enter **1**.

9. In the **Units** drop-down list, select **hr**.

10. In the **Cycle time ratio** field, enter **2**.

11. Select **OK**.

12. Select **Save** in the action pane.

13. Close the forms.

**Perform validation and activation**

The Mid-Range Speaker 2 PF production flow, Version 2 must be validated
to confirm that the changes have been correctly implemented.

1. Navigate to **Production control \> Setup \> Lean production flow \>
    Production flows.** The Production flows form opens.

2. Select the name of the Mid-Range Speaker 2 PF production flow. The
    **Production Flows** form for the selected production flow opens.

3. On the **Versions** FastTab, select Version **1**.

4. Select **Validate**. The **Validate production flow** dialog opens.

5. Select **OK**.

6. Select **Save** in the action pane.

7. Close the forms.

### Exercise #6: Create Kanban rules and schedule the Kanban job

A new car speaker remote has been developed to complement the car
speaker kits that are sold at USMF. The production flow is already
configured with multiple activities, and now the products and Kanbans
required to process the flow must be created

Products have been set up for the purchased un-programmed remote and for
the remote that will be programmed through the activities of the
production flow.

The bill of materials (BOM) has also been created, adding the purchased
unprogrammed remote as a BOM line.

Once the BOM is created, Kanban rules must be set up for the process
activity to program the remote and for the transfer activity to transfer
the programmed remote (now a finished good) to the warehouse and
location where it will be stored until it is sold

When the Kanban jobs are not automatically planned, they must be dragged
and dropped onto the desired period on the Kanban schedule board. You
can do that by using the Kanban board

The company called you to configure the above. Can you help?

You will have to do the following:

- Create the Kanban rule for the process activity

- Create the Kanban rule for the transfer activity

- Plan a Kanban on the Kanban board

#### Steps

**Create the Kanban rule for the process activity**

1. Navigate to **Product information management \> Lean manufacturing
    \> Kanban rules**.

2. Select **New**.

3. Select the **First plan activity** called
    **SpeakerTestAndPackaging**.

4. Expand the **Details** FastTab.

5. In the **Product**, select **L0001**.

6. Expand the **Quantities** FastTab

7. Enter a **Default quantity** of **100**.

8. Enter a **Fixed Kanban quantity** of **4**.

9. Expand the **Kanban and cards** FastTab.

10. Select the **Circulating cards** check box.

11. Change the **Card assignment** to **Automatic**.

12. Select **Save**.

13. Select the **Create cards** button.

14. Deselect the **Print new cards** box.

15. Select **Create**.

16. Switch to the **Kanbans** FastTab.

17. Select **Add**.

18. Verify that the default number of new Kanbans is 4.

19. Select **Create**.

20. Close all forms.

**Creating the Kanban rule for the transfer activity**

1. Navigate to **Product information management \> Lean manufacturing
    \> Kanban rules**.

2. Select **New**.

3. Change the **Type** to **Withdrawal**.

4. Update the **First plan activity** to
    **ReplenishSpeakerComponents**.

5. Expand the **Details** FastTab.

6. Enter the **Product L0001**.

7. Switch to the **Quantities** FastTab.

8. Enter the **Default quantity** of **10**.

9. Enter the **Fixed Kanban quantity** of 4.

10. Select **Save**.

11. Switch to the **Kanbans** FastTab.

12. Select **Add**.

13. Verify that the number of new Kanbans defaults to 4.

14. Select **Create**.

15. Close all forms.

**Planning a Kanban on the Kanban Board**

1. Navigate to **Production control \> Kanban \> Kanban job
    scheduling**.

2. Change Work cell to **1250**.

3. In the **Display job status** field select **Not scheduled**.

4. Select a Kanban job from the unplanned Kanban jobs, and then select
    the **Schedule** button. Repeat for the remaining Kanban jobs of
    your choice.

### Exercise #7: Process scheduled Kanbans for process and transfer jobs

After setting up the fixed Kanban rule from the previous exercise, the
company wonders if you can use the Kanban board to start processing
scheduled Kanban jobs.

Can you?

You will have to do the following:

- Process Kanbans on the Kanban board for process jobs

- Process Kanbans on the Kanban board for transfer jobs

#### Steps

**Process Kanbans on the Kanban board for process jobs**

The scheduled Kanbans are now ready to be processed. The **Production
control\>Kanban\>Kanban board for process jobs** will be used to
prepare, start, and complete the Kanbans.

1. Go to **Production control \> Kanban \> Kanban board for process
    jobs**.

2. When you open this form for the first time, all jobs from all work
    cells are shown. You can select the **Work cell** to filter the
    jobs.

3. Change the **Work cell** to **1250**.

4. Select the **000329 Kanban** to prepare.

5. Select **Prepare**.

6. To start the Kanbans, select **Start** button.

7. To complete the Kanbans, select **Complete**.

**Process Kanban on the Kanban board for transfer jobs**

The manufactured Kanban is now ready to be transferred to its final
location. The Kanban board for transfer jobs will be used to start and
complete the Kanban.

1. Go to **Production control \> Kanban \> Kanban board for transfer
    jobs**.

2. When entering the board for the first time you see all jobs from all
    production flows. Alternately, you can expand **Filters** FastTab
    and change **Production flow** to only show jobs for a specific
    production flow, such as Mid-Range Speaker 2 PF.

3. Select the Kanban with a card number M203.

4. To start the transfer, select **Start**.

5. To complete the transfer, select **Complete**.

### Exercise #8: Fulfill a sales order by planning a Kanban and produce an item (Bonus)

A sales order has been received for a green speaker set, which triggers
event Kanbans for the speaker set on the packaging work cell and the
speaker kits on the speaker assembly work cell.

The company want to record the production of the speaker kits and
speaker set to fulfil the customer sales order

How would you do that?

You will have to do the following:

- Create a sales order for the Kanban line event

- Plan the Kanbans

- Transfer the speaker set

#### Steps

**Create a sales order**

1. Navigate to **Sales and marketing \> Sales orders \> All sales
    orders**.

2. Select **New**.

3. Select the **Customer account** as **US-016**.

4. Select **OK**.

5. Enter **Item number** of "**L0026**".

6. Enter **Quantity** of "**12.00**".

7. Select a **Site** of **1** (scroll or tab right).

8. Select a **Warehouse** of **13**.

9. Select a **Location** of **13**.

    >**Note** If **Location** is not set on the sales order, go to **Sales order
line** \> **Display** and select the **Dimensions** button. Choose the location and configuration.

10. Select **Configuration 01**.

11. Select on **Save**.

12. Select the **Product and supply \> View pegging tree** menu button
    to view the event Kanbans created for the sales order.

**Plan the Kanbans**

1. Navigate to **Production control \> Kanban \> Kanban schedule
    board**.

2. Change **Work cell** to **the value present under Kanban jobs Fast
    tab under View Pegging tree.**.

3. Plan the Kanban for that workcell by selecting the Kanban job in the
    board.

4. Close all forms.

5. Navigate to **Production control \> Kanban \> Kanban board for
    process jobs**.

6. Change **Work cell** to the one that you have seen in the view
    pegging tree.

7. Highlight the desired Kanbans and select **Start**.

8. Select **Complete**.

9. Change **Work cell** to the one which you have seen in the view
    pegging tree

10. Highlight a Kanban and switch to the **Pegging** FastTab on the
    **Kanban board for process jobs** work cell form. View the complete
    lower level speaker set Kanbans on the pegging tree.

11. Select **Start**.

12. Select **Complete**.

**Transfer the speaker set**

1. Navigate to **Production control \> Kanban \> Kanban board for
    transfer jobs**.

2. Expand **Filters** FastTab.

3. Select a **Production Flow**.

4. Select **Update picking list** on the Transfer tab in the action
    pane.

5. Select **Add picking** line.

6. Select **Confirm** pick all.

7. Close the form.

8. Select **Start**.

9. Select **Complete**.
