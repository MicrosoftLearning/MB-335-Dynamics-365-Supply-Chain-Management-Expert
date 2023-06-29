---
lab:
    title: 'Case study 1B Discrete, Process and Lean manufacturing features'
    module: 'Module 3 Implement production methods'
---

# Module 3 Module 3 Implement production methods

## Case study 1B Discrete, Process and Lean manufacturing features

### Exercise #1: Create an approved vendor list and setting method to Warning Only (Bonus)

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

### Exercise #2: Create items with different production types

Contoso Process Company (USPI) has purchased a small oil refinery and
will start to manufacture gasoline from a stream of crude oil.

This process produces kerosene and diesel fuel as co-products and
wastewater as a by-product.

You will help the product designer to create the items listed here
within finance and operations using different production types to assist
in the creation of formulas or recipes

- Product Number: P15000

  - Product Name: Gasoline

  - Production Type: Formula

- Product Number: P16000

  - Product Name: Kerosene

  - Production Type: Co-Product

- Product Number: P17000

  - Product Name: Diesel Fuel

  - Production Type: Co-Product

- Product Number: P18000

  - Product Name: Waste Water

  - Production Type: By-Product

- Product Number: M12000

  - Product Name: Crude Oil

  - Production Type: None

You will have to do the following:

- Create a new formula product

- Create the new\
    co-products

- Create the new byproducts

- Create the new raw material

#### Steps

**Create a new formula product**

1. In **USPI**, go to **Product information management \> Products \>
    Released products**.

2. Select **New**.

3. In the **Product number** field, enter or select **P15000**.

4. In the **Product name** field, enter or select **Gasoline**.

5. In the **Item model group** field, enter or select **PI FEFO**
    (Note: For prioritized consumption on limited shelf life, FEFO is
    recommended.)

6. In the **Item group** field, enter or select **Cleaner**.

7. In the **Storage dimension group** field, enter or select **Site
    WH**

8. In the **Tracking dimension group** field, enter or select
    **Batch-CP**. (Note: To use the shelf-life settings on the released
    products details page on the General FastTab, set the **Tracking
    dimension group** field to a tracking dimension group that is set up
    to track the batch dimension. You can set this field only when
    you\'re first creating a product. If the dimension value is set to
    **None**, the option to edit the shelf life field will be disabled.
    You can\'t change the value for existing products.)

9. In the **Inventory unit** field, enter or select **gal**.

10. In the **Purchase unit** field, enter or select **gal**. (Note: you
    may need to change the dropdown in the selection menu to **All**.)

11. In the **Sales unit** field, enter or select **gal**. (Note: you may
    need to change the dropdown in the selection menu to **All**.)

12. In the **BOM unit** field, enter or select **gal**. (Note: you may
    need to change the dropdown in the selection menu to **All**.)

13. Select **OK**.

14. Expand the **Engineer** FastTab and select **Formula** in the
    **Production type** field.

15. Expand the **Manage inventory** Fast Tab and enter **365** in the
    **Shelf life period in days** field.

16. Select **Save**.

17. Close the page.

**Create the new co-products**

1. Select **New**.

2. In the **Product number** field, enter **P16000**.

3. In the **Product name** field, enter **Kerosene**.

4. In the **Item model group** field, enter or select PI FEFO

5. In the **Item group** field, enter or select Cleaner.

6. In the **Storage dimension group** field, enter or select SiteWH

7. In the **Tracking dimension group** field, enter or select
    **Batch-CP**.

8. In the **Inventory unit** field, enter or select **gal**.

9. In the **Purchase unit** field, enter or select **gal**.

10. In the **Sales unit** field, enter or select **gal**.

11. In the **BOM unit** field, enter or select **gal**.

12. Select **OK**.

13. Expand the **Manage inventory** Fast Tab and enter **365** in the
    **Shelf life period in days** field.

14. Expand the **Engineer** Fast Tab and select **Co-product** in the
    **Production type** field.

15. In the **Planning formula** field, enter **P15000**.

16. Select **Save**.

17. Close the page.

18. Select **New**.

19. In the **Product number** field, enter or select **P17000**.

20. In the **Product name** field, enter or select **Diesel Fuel**.

21. In the **Item model group** field, enter or select **PI FEFO**.

22. In the **Item group** field, enter or select **Cleaner**.

23. In the **Storage dimension group** field, enter or select
    **SiteWH**.

24. In the **Tracking dimension group** field, enter or select
    **Batch-CP**.

25. In the **Inventory unit** field, enter or select **gal**.

26. In the **Purchase unit** field, enter or select **gal**.

27. In the **Sales unit** field, enter or select **gal**.

28. In the **BOM unit** field, enter or select **gal**.

29. Select **OK**.

30. Expand the **Manage inventory** Fast Tab and enter **365** in the
    **Shelf life period in days** field.

31. Expand the **Engineer** Fast Tab and select **Co-product** in the
    **Production type** field.

32. In the **Planning formula** field, enter **P15000**.

33. Select **Save**.

34. Close the page.

**Create the new by-products**

1. Select **New**.

2. In the **Product number** field, enter or select **P18000**.

3. In the **Product name** field, enter or select **Waste Water**.

4. In the **Item model** group field, enter or select PI FEFO

5. In the **Item group** field, enter or select Cleaner.

6. In the **Storage dimension group** field, enter or select SiteWH.

7. In the **Tracking dimension group** field, enter or select Batch-CP.

8. In the **Inventory unit** field, enter or select **gal**.

9. In the **Purchase unit** field, enter or select **gal**.

10. In the **Sales unit** field, enter or select **gal**.

11. In the **BOM unit** field, enter or select **gal**.

12. Select **OK**.

13. Expand the **Manage inventory** Fast Tab and enter **365** in the
    **Shelf life period in days** field.

14. Expand the **Engineer** Fast Tab and select **By-product** in the
    **Production type** field.

15. Select **Save**.

16. Close the page.

**Create the new raw material**

1. Select **New**.

2. In the **Product number** field, enter or select **M12000**.

3. In the **Product name** field, enter or select **Crude Oil**.

4. In the **Item model group** field, enter or select PI-FEFO.

5. In the **Item group** field, enter or select a value Cleaner.

6. In the **Storage dimension group** field, enter or select SiteWH.

7. In the **Tracking dimension group** field, enter or select a
    Batch-CP.

8. In the **Inventory unit** field, enter or select **gal**.

9. In the **Purchase unit** field, enter or select **gal**.

10. In the **Sales unit** field, enter or select **gal**.

11. In the **BOM unit** field, enter or select **gal**.

12. Select **OK**.

13. Expand the **Manage inventory** Fast Tab and enter **365** in the
    **Shelf life period in days** field.

14. Expand the **Engineer** Fast Tab and select and in the **Production
    type** field, select None.

15. Select **Save**.

16. Close all pages.

### Exercise #3: Create and activate a formula using different product types

The engineering department has finished the review of the data in the
new refinery and determined the formula should be as specified here.

The product definition employee wants to create the formula and assign
the co-products and by-products to the formula and cost allocation.

He asked for your help. Can you help?

- Product Number: P15000

- Product Name: Gasoline

- Formula Size: 500 gal

- Formula Line: M12000 (Crude Oil), QTY 1000 gal

- Formula Line: M2001 (DI Water), QTY 600 gal

- Co-Product Line: P16000 (Kerosene), QTY 50 gal 10% cost allocation

- Co-Product Line: P17000 (Diesel Fuel), QTY 350 gal 32% cost
    allocation

- By-Product Line: P18000 (Waste Water), QTY 600 gal, 5% cost
    allocation

- Approved by: Glen John

You will have to do the following:

- Create a formula

- Add formula lines to the formula

- Add co-products and by-products with cost allocation

- Approve and activate the formula

#### Steps

**Create a formula for part P15000**

1. Go to **Product information management\>Products\>Released
    products**.

2. Use the Quick Filter to find records. For example, filter on the
    Item number field with a value of **p15000**. Note the lowercase --
    it is not case sensitive.

3. Select the ellipsis, if needed, to get to the **Engineer** tab on
    the action pane.

4. Select **Formula versions**.

5. Select **New**.

6. Select **Formula and formula version**.

7. In the **Formula number** field, enter or select **GAS001**.

8. In the **Name** field, enter or select **Gasoline**.

9. In the **Site** field, enter or select **1**.

10. Select **OK**.

11. In the **Lines** or **Header** field, select **Header**.

12. In the **Formula versions** grid, set the **Formula size** field to
    **500.00**.

13. Select **Save**.

**Add Formula Lines to Formula**

1. In the **Lines** or **Header** field, select **Lines**.

2. Select **New**.

3. In the **Item number** field, enter or select **M12000**. (Note:
    When you select **New**, you may need to change the dropdown in the
    selection menu to **Other**, select the Item number and then select
    **Ok**.)

4. In the **Warehouse** field, enter or select 11.

5. Set **Quantity** to **1000**.

6. Select **New**.

7. In the **Item number** field, enter or select **M2001**. (Note: When
    you select **New**, you may need to change the dropdown in the
    selection menu to **Other**, select the Item number and then select
    **Ok**.)

8. Set **Quantity** to **600**.

9. Select **Save**.

10. Close the page.

**Add Co-Products and By-Products with Cost Allocation**

1. In the Action bar, select \**Formula version* and then select
    **Co-products**.

2. Select **New**.

3. In the **Item number** field, enter or select **P16000**.

4. In the **Warehouse** field, enter or select 11.

5. Set **Quantity** to **50**.

6. In the **Co-product cost allocation** field, select **Manual**.

7. Set **Cost allocation percent** to **10**.

8. Select **Save**.

9. Select **New**.

10. In the **Product enter or select** dropdown, select **By-product**.
    In the **Item number** field, enter or select **P17000**.

11. In the **Warehouse** field, enter or select **11**.

12. Set **Quantity** to 350.

13. In the **By-product cost allocation** field, select Percent .

14. Set **By-Product cost** **allocation percent** to **32**.

15. Select **Save**.

16. Select **New**.

17. In the **Item number** field, enter or select **P18000**.

18. In the **Warehouse** field, enter or select 11

19. Set **Quantity** to **600**.

20. In the **By-product cost allocation** field, select **Percent**.

21. Set **By-product burden amount** to **5**.

22. Select **Save**.

23. Close the page.

**Approve and activate the formula**

1. Select **Formula version** and then select **Approval**.

2. In the **Approved by** field, enter or select **000528** for Glen
    John.

3. Slide the toggle button to **Yes** for **Do you also want to approve
    the formula?** option.

4. Select **OK**.

5. Select **Activate**.

6. Close the page.

### Exercise #4: Create a new formula with a version from the released products form (Bonus)

The marketing department at USP2 Contoso Orange Juice factory has
determined the need for production of a new product for Frozen Apple
Juice Concentrate.

The product designer asked you to help create a formula version with the
following details

Can you do so?

- Product Number: P7100

- Product Name: Frozen Apple Juice Concentrate

- Formula Size: 1000 gal

- Formula Line: M9103 (Apples), QTY 800

- Formula Line: M8001 (Asorbic Acid),\
    QTY 660

- Formula Line: M8003 (Vitamin A), QTY 40

- Formula Line: M8004 (Vitamin C), QTY 18

- Formula Line: M7003 (Sucrose), QTY 33

- Formula Line: M8008 (Can), QTY 2400

- Approved by: Glen John

You will have to do the following:

- Create a new product.

- Create a formula.

- Create formula lines.

- Approve and activate the formula

#### Steps

**Create a new product**

1. In the **USP2** company go to **Product information
    management\>Products\>Released products.**

2. Select **New**.

3. In the **Product number** field, enter or select **P7100**.

4. In the **Product name** field, enter or select **Frozen Apple Juice
    Concentrate**.

5. In the **Search name** field, enter or select **FrozenAppleJuice**.

6. In the **Item model group** field, enter or select FEFO.

7. In the **Item group** field, enter or select AdditiveRM.

8. In the **Storage dimension group** field, enter or select SiteWH.

9. In the **Tracking dimension group** field, enter or select Batch-CP.

10. In the **Inventory unit** field, enter **lb**.

11. In the **Purchase unit** field, enter or select **lb**.

12. In the **Sales unit** field, enter or select **lb**.

13. In the **BOM unit** field, enter or select **lb**.

14. Select **OK**.

15. In the **Production type** field in the Engineer FastTab, select
    **Formula**.

16. In the **Shelf life period in days** field in the Manage inventory
    FastTab, enter or select **180**.

17. Select **Save**.

**Create a formula**

1. Select **Formula versions** in the Engineer tab in the action pane.

2. Select **New**.

3. Select **Formula and formula version**.

4. In the **Formula** number field, enter or select **FOR-7100**.

5. In the **Name** field, enter or select **For making Frozen Apple
    Juice Concentrate**.

6. In the **Site** field, enter or select **1**.

7. Select **OK**.

**Create formula lines**

1. In the **Lines** or **header** field, select **Header**.

2. Set **Formula size** to 1000.

3. Set **From formula size** in the Formula versions Fast Tab to
    **1000**.

4. In the **Lines** or **header** field, select **Lines**.

5. In the Formula lines fast tab, select **New**.

6. In the **Item number** field, enter or select **M9103**. (Note: When
    you select New, you may need to change the dropdown in the selection
    menu to **Other**, select the Item number and then select Ok.)

7. Set **Quantity** to **800**.

8. Select **New**.

9. In the **Item number** field, enter or select **M8001**.

10. Set **Quantity** to **660**.

11. Select **New**.

12. In the **Item number** field, enter or select **M8003**.

13. Set **Quantity** to **40**.

14. Select **New**.

15. In the **Item number** field, enter or select **M8004**.

16. Set **Quantity** to **18**.

17. Select **New**.

18. In the **Item number** field, enter or select **M7003**.

19. Set **Quantity** to **33**.

20. Select **New**.

21. In the **Item number** field, enter or select **M8008**.

22. Set **Quantity** to **2400**.

23. Select **Save**.

**Approve and activate the formula**

1. Select **Formula** and then select **Approve formula**.

2. In the **Approved by** field, enter or select **000528** for Glen
    John.

3. Select **OK**.

4. In the **Lines** or **Header** field, select **Header**.

5. Select **Approval** in the versions section.

6. In the **Approved by** field, enter or select **000528** for Glen
    John.

7. Select **OK**.

8. Select **Activate**.

9. Close the page.

### Exercise #5: Revise, update and activate a formula (Bonus)

Analysis of the production orders for P8000 in company USP2 has shown
that the scrap factors and consumption amount of part P6000 need to be
updated.

You want to formula revise, update, approve, and activate the formula
with an effective date of current date

You will have to do the following:

- Copy the existing formula

- Update line

- Date out the old version and date in the new version

- Approve and activate the formula

#### Steps

**Copy the existing formula**

1. In the **USP2** company go to **Product information
    management\>Products\>Released products**.

2. Use the Quick Filter to filter on the Item number field with a value
    of **P8000**.

3. In the list, select the link in the selected row.

4. Select **Formula versions** in the Engineer tab on the action pane.

5. Select **New**.

6. Select **Formula and formula version**.

7. In the **Formula number** field, enter or select **F01**.

8. In the **Name** field, enter or select **V01**.

9. Set the **Copy** to **Yes**.

10. In the **Site** field, enter or select **1**.

11. Select **OK**.

12. In the **Formula version** field, select **For-00001**.

13. Select **OK**.

**Update the line**

1. In the list, find and select the record for **P6000**.

2. Set **Quantity** to **0.35**.

3. Expand the Line details Fast Tab then select the **Setup** tab.

4. In the **Variable scrap** field, enter 1

5. Select **Save**.

6. Close the page.

**Date out the old version and date in the new version**

1. In the list, find and select the original formula version
    **For-00002**.

2. In the **To date** field, set the date to **12/14/2020.**

3. Select **Save**.

4. In the list, find and select the new formula version **F01**.

5. In the **From date** field, set the date to. **12/15/2023**

6. Select **Save**.

**Approve and activate the formula**

1. Select **Formulas** \> **Formula**.

2. Select **Approve formula**.

3. In the **Approved by** field, enter or select **000528** for Glen
    John and click **OK**.

4. Close the screen to go back to the Formula versions screen.

5. Select **Formula version** \> **Approval**.

6. In the **Approved by** field, enter or select **000528** for Glen
    John

7. Select **OK**.

8. Select **Activate**.

9. Close the page.

### Exercise #6: Use the scalability feature to create a new formula

Your manufacturing plant in company USP2 has obtained a new mixer that
is 1.5 times the size of the current mixer used to make part P9500.

Engineering has determined that the vitamin compounds do not need to
increase in quantity, but the other ingredients do.

Use the formula scalability feature to create a new formula for the
larger size based on the existing formula for the part

You will have to do the following:

- Copy the existing formula

- Verify the lines are flagged as scalable for P9500 (except for the
    vitamin compounds)

- Update the formula size

- Approve and activate the formula

#### Steps

**Copy the existing formula**

1. IN **USP2** company go to **Product information
    management\>Products\>Released products**.

2. Use the Quick Filter to filter on the **Item number** field with a
    value of **P9500**.

3. In the list, select the link in the selected row.

4. Select **Formula versions** in the Engineer tab in the action pane.

5. Select **New**.

6. Select **Formula and formula version**.

7. In the **Formula number** field, enter or select **P9500V0**.

8. In the **Name** field, enter or select **V0**.

9. Select the **Copy** option.

10. In the **Site** field, enter or select **1**.

11. Select **OK**.

12. In the **Formula version** field, select the current version
    **FOR-00013.**

13. Select **OK**.

**Verify the lines are flagged as scalable for P9500 (except for the
vitamin compounds)**

1. In the lines, find the vitamin compounds.

2. Select or clear the **Scalable** check boxes.

> **Note** Make sure that the Scalable check boxes for other products are
> checked except for Vitamin A, Vitamin C, Vitamin E.*

3. Select **Save**.

**Update the formula size**

1. In the **Lines or header** field, select **header**

2. Set **Formula size** to **1500**.

3. Set **From formula size** to **1500**.

4. Select **Save**.

**Approve and activate the formula**

1. In the Lines or header field, select **lines**.

2. Select Edit

3. Select **Approve formula**.

4. In the **Approved by** field, enter or select 000528 for Glen John

5. Select **OK**.

6. In the **Lines or header** field, select **header**.

7. Select **Approval** in the **Versions** grid.

8. In the **Approved by** field, enter or select 000528 for Glen John

9. Select **OK**.

10. Select **Activate**.

11. Close the page.

### Exercise #7: Create and activate a percentage-based formula (Bonus)

Company USP2 has been contracted to make a new orange juice with the
following volume percentages for the final mixture.

The mixture should also have vitamin C and vitamin A added per the
mixing instructions given here.

The volume batch size is to be 1500 gallons

You were asked to use this info to create the formula. Can you help?

\| Ingredient \| Recipe percent/ \| \| \| quantity \|
\|\-\-\-\-\-\-\-\-\-\-\--\|\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--\|
\| P9500 \| 5% \| \| M9001 \| 92% \| \| M7004 \| 3% \| \| M8004 \| 1.33
lb/1500 gal. \| \| M8003 \| 1.1 LB/1500 gal. \|

You will have to do the following:

- Create a new release product

- Copy the existing formula for P9500

- Verify the lines are flagged as scalable for P9500 (except the
    vitamin compound)

- Update the formula size

- Approve and activate the formula

#### Steps

**Create a new released product**

1. In the **USP2** company go to **Product information
    management\>Products\>Released products**.

2. Select **New**.

3. In the **Product number** field, enter or select **\'P6100\'**.

4. In the **Product name** field, enter or select '**Orange Juice\'**.

5. In the **Search name** field, enter or select **\'Orange Juice\'**.

6. In the **Item model group** field, enter or select FEFO.

7. In the **Item group field**, enter or select AdditiveRM.

8. In the **Storage dimension group** field, enter or select SiteWH.

9. In the **Tracking dimension group** field, enter or select Batch-CP.

10. In the **Inventory unit** field, enter or select **gal**.

11. In the **Purchase unit** field, enter or select **gal**.

12. In the **Sales unit** field, enter or select **gal**.

13. In the **BOM unit** field, enter or select **gal**.

14. Select **OK**.

15. In the **Production type** field in the Engineer FastTab, select
    **\'Formula\'**.

16. In the **Shelf life period in days** field in the Manage inventory
    Fast Tab, enter **180**.

17. Select **Save**.

**Copy the existing formula for P9500**

1. Go to **Product information management\>Products\>Released
    products**.

2. Use the Quick Filter to filter on the Item number field with a value
    of **\'P9500\'**.

3. In the list, select the link in the selected row.

4. Select **Formula versions** in the Engineer tab in the action pane.

5. Select **New**.

6. Select **Formula and formula version**.

7. In the **Formula number** field, enter or select **P9500V0**.

8. In the **Name** field, enter or select **V0**.

9. Select the **Copy** option.

10. In the **Site** field, enter or select **1**.

11. Select **OK**.

12. In the **Formula version** field, select the current version.

13. Select **OK**.

**Verify the lines are flagged as scalable for P9500 (except for the
vitamin compounds)**

1. In the lines, find the vitamin **compounds**.

2. Select or clear the **Scalable** check boxes.

    > **Note** Make sure that the Scalable check boxes for other products are
    > checked except for Vitamin A, Vitamin C, Vitamin E.

3. Select **Save**.

**Update the formula size**

1. In the Lines or header field, select **header**.

2. Set the version's **Formula size** to **\'1500\'**.

3. Set the version's **From formula size** to **\'1500\'**.

4. Select **Save**.

**Approve and activate the formula**

1. In the Lines or header field, select **lines**.

2. Select **Save**.

3. Select **Approve formula**.

4. In the **Approved by** field, enter or select **000528** for Glen
    John.

5. Select **OK**.

6. In the Lines or header field, select **header**.

7. Select **Approval** in the **Versions** grid.

8. In the **Approved by** field, enter or select **000528** for Glen
    John.

9. Select **OK**.

10. Select **Activate**.

11. Close all pages.

### Exercise #8: Change a linear consumption to a step-wise consumption

In company USP2, the formula for product P9500 should be updated.

Formula line M9003 needs to be changed from a linear consumption to a
step-wise consumption

The consumption on the line shall be:

- 0-1400: 5.5

- 1400-2400: 10.6

- 2400+: 15.8

The company employee is not sure how to do so and asked for your help.
Can you help?

You will have to do the following:

- Copy the existing formula\
    for P9500

- Set the line for M9003 in the new formula to step-wise consumption
    and set the\
    step levels

- Date out the old formula and date in the new one

- Approve and activate the formula

#### Steps

**Copy the existing formula for P9500**

1. Go to **Product information management \> Products \> Released
    products**.

2. Use the Quick Filter to filter on the **Item number** field with a
    value of **P9500**.

3. In the list, select the link in the selected row for **P9500**.

4. Select **Engineer** \> **Formula** \> **Formula versions**.

5. Select **New**.

6. Select **Formula and formula version**.

7. In the **Formula number** field, enter or select **P9500V1**.

8. In the **Name** field, enter or select **V1**.

9. Select the **Copy** option.

10. In the **Site** field, enter or select 1.

11. Select **OK**.

12. In the **Formula version** field, select the current version

13. Select **OK**.

**Set the line for M9003 in the new formula to step-wise consumption and
set the step levels**

1. In the lines, find the line for **M9003**.

2. Select the **Setup** tab in line details.

3. In the **Formula** field, select **Step**.

4. Select the **Step consumption** tab.

5. Set **Quantity** to **5.5**.

6. Select **New**.

7. Set **From series** to **1400**.

8. Set **Quantity** to **10.6**.

9. Select **New**.

10. Set **From series** to **2400**.

11. Set **Quantity** to **15.8**.

12. Select **Save**.

13. Close all pages.

**Date out the old formula and date in the new one**

1. Go to **Product information management\>Products\>Released
    products**.

2. Use the Quick Filter to filter on the **Item number** field with a
    value of **P9500**.

3. In the list, select the link in the selected row for **P9500**.

4. Select Engineer \> Formula \> **Formula versions**.

5. In the list, find and select the old formula.

6. Select **Edit**.

7. In the **To date** field, set the date to **12/27/2023**

8. Select **Save**.

9. In the list, find and select the new formula.

10. In the **From date** field, set the date to **12/28/2023.**

11. Select **Save**

**Approve and activate the formula**

1. Select **Formulas\>Formula**. Select **Approve Formula.**

2. In the **Approved by** field, enter or select **000528** for Glen
    John. Click OK.

3. Select Header tab then click Approval and enter **000528** for Glen
    John.

4. Select **OK**.

5. Select **Activate**.

### Exercise #9: Set up commodity pricing (Bonus)

In company USP2, the price of apples, part M9103, is to be tracked based
upon the NYMEX commodity exchange pricing of apples.

The sales price of the Apple Pie, part P9300, manufactured from this
sugar should be based on a margin of 45 percent and a cost multiple of
1.25 for all quantities.

The pricing employee wants to set up the cost basis and pricing template
for this scenario. She is not sure how to do so and asked for your help.

Can you help?

You will have to do the following:

- Configure item P9100

- Create a cost basis

- Create a pricing template

- Create a quantity and margin template

- Complete the inventory parameter setup

- Set up pricing calculation

#### Steps

**Configure an item**

1. Go to **Product information management \> Products \> Released
    products**.

2. Use the **Quick Filter** to filter on the **Item number** field with
    a value of **P9100**.

3. On the Action Pane, select **Manage inventory**.

4. Select **Default order settings**.

5. Select **Edit**.

6. In the **Default order type enter** field, select **Production**.

7. Select **Save**.

8. Close all pages.

**Create a cost basis**

1. Go to **Inventory management \> Setup \> Commodity pricing \> Cost
    basis type.**

2. Select **New** if necessary.

3. In the **Cost basis type** field, enter **NYMEX**.

4. In the **Description** field, enter **New York Mercantile
    Exchange**.

5. Select **Save**.

6. Close the page.

**Create a pricing template**

1. Go to **Inventory management \> Setup \> Commodity pricing \>
    Pricing template**.

2. Select **New**.

3. In the **Pricing template** field, enter **Apples**.

4. In the **Description** field, enter **Apples**.

5. Select **Save**.

**Create a quantity and margin template**

1. Select **Quantity and margin template**.

2. Select **New**.

3. In the **Item relation** field, enter **P9100**.

4. In the **Site** field, enter **1**.

5. Set **Cost multiplier** to **1.25**.

6. Set **Margin percentage** to **45**.

7. In the **Warehouse** field, enter **12**. If it's not visible, find
    it in the Dimension fast tab.

8. Select **Save**.

9. Close the page.

**Complete the inventory parameter setup**

1. Go to **Inventory management \> Setup \> Inventory and warehouse
    management parameters**.

2. Select the **Commodity pricing** tab.

3. In the **Dimension set** field, enter or select **MA+BU**.

4. In the **Cost basis type** field, enter or select **NYMEX**.

5. Select **Yes** in the **Keep BOM/Formula calculations** field.

6. Right select **Trade agreement** and view details.

7. Select **New**.

8. In the **Name** field, enter **Price_S**.

9. In the **Description** field, enter **Sales Price Adjustment
    Journal**.

10. In the **Relation** field, select **Price (sales)**.

11. Select **Save**.

12. Close the page.

13. In the **Trade agreement** field, enter or select **Price_S**.

14. Select **Save**.

15. Close the page.

**Set up pricing calculation**

1. Go to **Inventory management \> Periodic tasks \> Commodity pricing
    \> Pricing calculation.**

2. Select **New**.

3. Note that the **Cost basis type** field is set to **NYMEX**.

4. In the **Run effective date** field, enter todays date.

5. In the **Run expiry date** field, enter a date in the future.

6. Select **Save**.

7. Close the page.

### Exercise #10: Change a price calculation and update trade agreements

In company USP2, the price of apples, part M9103, is to be tracked based
upon the NYMEX commodity exchange pricing of apples.

The sales price of the applesauce manufactured from the apples is to be
based upon the fluctuations in the pricing of the apples from 3/20/23 to
3/27/23

You will have to do the following:

- Complete the price calculation

- Review the price calculation data and create trade agreements

- Post the trade agreements that are created

#### Steps

**Complete the price calculation**

1. Go to **Inventory management \> Periodic tasks \> Commodity pricing
    \> Create price and margin data**.

2. In the Pricing calculation field, enter or select **000001** for
    NYMEX.

3. In the Pricing template field, enter or select **Apples**.

4. Select **OK**.

**Review the price calculation data and create trade agreements**

1. Go to **Inventory management \> Periodic tasks \> Commodity pricing
    \> Price margin update**.

2. If the price calculations are completed successfully, you will see
    your new pricing. Select **Lines**.

3. Select **Update trade agreements**.

4. Select **OK**.

5. Close the page.

6. In the list, find and select the desired record.

7. Select **Lines**.

8. Select **Update trade agreements**.

9. Select **OK**.

10. Close the page.

**Post the trade agreements**

1. Go to **Sales and marketing \> Prices and discounts \> Trade
    agreement journals**.

2. Select **Lines**.

3. Select **Post**.

4. Select **OK.**

5. Select **Lines**.

6. Select **Post**.

7. Select **OK**.

8. Close the page.

### Exercise #11: Setting up a commodity price calculation

In company USP2, the price of apples, part M9103, is to be tracked based
upon the NYMEX commodity exchange pricing of apples. The sales price of
the applesauce manufactured from the apples is to be based upon the
fluctuations in the pricing of the apples. The weekly pricing for the
week of 03/20/2023 and 03/27/2023 has been received as 0.14/lb. and
0.15/lb., respectively

You will have to do the following:

- Create a pricing calculation

- Enter commodity pricing data

- Create a pricing calculation

- Enter commodity pricing data

#### Steps

**Create a pricing calculation**

1. Go to **Inventory management \> Periodic tasks \> Commodity pricing
    \> Pricing calculation**.

2. Select **New**.

3. In the **Cost basis type** field, enter or select **NYMEX**.

4. In the **Site** field, enter **1**.

5. In the Run effective date field, set the date to **2023-03-20** or
    your local equivalent.

6. In the **Run expiry date** field, set the date to **2023-03-23** or
    your local equivalent.

7. Select **Save**.

**Enter commodity pricing data**

1. Select **Commodity pricing**.

2. Select **New**.

3. In the Item number field, enter **M9103**.

4. In the **Warehouse** field, enter or select 12.

5. Set **New cost** to **0.14**.

6. Select **Save**.

7. Close the page.

**Create a pricing calculation**

1. Select **New**.

2. In the **Cost basis type** field, enter or select **NYMEX**.

3. In the **Site** field, enter **1**.

4. In the **Run effective date** field, set the date to **2023-03-25.**

5. In the **Run expiry date** field, set the date to **2023-03-27**.

6. In the **Previous run** field, enter or select a value.

**Enter commodity pricing data**

1. Select **Commodity pricing**.

2. Select **New**.

3. In the **Item number** field, enter **M9103**.

4. In the **Warehouse** field, enter or select 12.

5. Set New cost to **0.15**.

6. Select **Save**.

7. Close the page.

### Exercise #12: Creating PSDS lists, records and file uploads for product compliance

In company USP2, product M7001, sulfur dioxide, has been setup as a
regulated and restricted product. A new PSDS has been obtained from the
vendor and must be attached to the item. Using the attached file, create
the PSDS record and activate it based upon an effective date range of
6/1/2020to 5/31/2020

You will have to do the following:

- Create a PSDS list

- Create a PSDS record

- Upload a PSDS file

#### Steps

**Create a PSDS list**

1. Go to **Inventory management \> Setup \> Product compliance \>
    Product safety data sheet validity**.

2. Select **New**.

3. In the Country/region field, enter **USA**.

4. Select **Save**.

5. Close the page.

**Create a PSDS record**

1. Go to **Product information management \> Products \> Released
    products**.

2. Use the Quick Filter to filter on the Item number field with a value
    of **M7001**.

3. On the Action Pane, select **Manage inventory**.

4. Select **Safety data sheet**.

5. Select **New**.

6. In the **Document Name** field, enter or select PSDS record.

7. Select **Yes** in the **Active** field.

8. In the **Country/region** field, enter or select USA.

9. In the **Approval** source field, enter or select Glen John.

10. In the **Major version** field, enter 10.

11. In the **Approval date** field, set the date to 2023-03-22 or your
    local equivalent.

12. In the **Effective date** field, set the date to 2023-03-25 or your
    local equivalent.

13. In the **Expiry date** field, set the date to 2023-03-26 or your
    local equivalent.

14. Select **Save**.

**Upload a PSDS file**

1. Select **Attach** (the paper clip near the top right).

2. Select **New**.

3. Select **File**.

4. Select **Browse**

5. Select the MSDS file, or any file to act as it.

6. In the Restriction field, select **External**.

7. Select **Save**.

8. Close the page.

9. Refresh the page.

10. Select **Open** document.

11. Close the page.

### Exercise #13: Add reporting details for an item

The product safety manager wants to add reporting details for product
M7001, Set the OSHA Product Name to "Sulfur Dioxide", and give it a
threshold quantity of 5, an EHS reportable quantity of 500, and a TPQ of
500. The CAS number should be set to 7446-09-5.

The annual usage quantity must also be updated for reporting

You were asked to show the safety manager how to do that.

Can you help?

You will have to do the following:

- Enter product reporting details

- Enter the CAS number

- Update annual usage quantities

#### Steps

**Enter product reporting details**

1. Go to **Product information management \> Products \> Released
    products**.

2. Use the Quick Filter to filter on the Item number field with a value
    of **m7001**.

3. On the Action Pane, select **Manage inventory**.

4. In the **Compliance** group, select **Reporting details**.

5. Select **Edit**.

6. In the **OSHA product name** field, enter or select **Sulfur
    Dioxide**.

7. Set the OSHA threshold quantity to **5**.

8. Set the EHS reportable quantity to **500**.

9. Set the EHS threshold planning quantity to **500**.

10. Select **Save**.

**Enter the CAS number**

1. Select **Item CAS relations**.

2. In the **CAS number** field, enter or select **7446-09-5**.

3. In the **CAS name** field, enter or select **Sulfur Dioxide**.

4. Select **Save**.

5. Close the page.

**Update annual usage quantities**

1. Select **Update quantities**.

2. Close the page.

### Exercise #14: Create a sales order and printing a PSDS

Product M7001, sulfur dioxide, has been setup as a regulated and
restricted product.

A new request for 100 oz of M7001 from customer US-031 on April 4, 2023
has been received.

The sales representative wants to enter the sales order and make a note
of the messages received.

Ship the material and verify that the valid PSDS is printed upon posting
of the packing list.

The sales manager is confused about how to do that.

You were asked to help.

Can you help?

You will have to do the following:

- Create a sales order for item M7001

- Complete the reservation

- Post the packing slip and print the PSDS

#### Steps

**Create a sales order**

1. Go to **Accounts receivable \> Orders \> All sales orders**.

2. Select **New**.

3. In the **Customer account** field, enter or select **us-031.**

4. In the **Warehouse** field (General section), enter or select
    **11**.

5. In the **Requested receipt date** field, set the date to a near
    future date.

6. Select **OK**.

7. In the Item number field, enter or select **m7001**.

8. Set Quantity to **100**.

9. In the **Unit price** field, enter 10.

10. Select **Save**.

**Complete the reservation**

1. Select **Inventory**.

2. Select **Reservation**.

3. Select **Reserve lot**.

4. Close the page.

**Post the packing slip and print the PSDS**

1. Select **Pick and pack \> Post packing slip**.

2. Select **OK**.

3. Select **OK**.

4. Verify that the PSDS was printed if that option was desired.

5. Close the page.

### Exercise #15: Create and associate a batch attribute

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

### Exercise #16: Create a new batch number and manually record the batch attribute

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

3. Click **New** then click Attribute dropdown icon and select
    **MeltingPoint**. Select **Load item attributes**.

4. In the **Attribute value** field, enter or select **163**.

5. Select **Save**.

6. Close all pages.

### Exercise #17: Create quality orders and verify batch attributes

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

11. Note the purchase order number.

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

### Exercise #18: Complete a batch reservation using an attribute requirement

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

### Exercise #19: Set a partial visibility catch weight item

At company USP2, a new catch weight item for sugar in\
20-pound bags must be created as item M7010.

The inventory manager is struggling to do the following:

- Create the new released product as a partial visibility catch weight
    item.

- After creating the item, create a new purchase order for 15 bags.

- The bags are to be received using the arrival overview process, and
    the total weight for the 15 bags of sugar should be specified

You are the MFG functional consultant and they asked you to help. Can
you help?

You will have to do the following:

- Create the released product and set catch weight conversions

- Create purchase order for\
    15 bags of item M7010

- Create and post an arrival journal for the purchase order

#### Steps

**Create the released product and set catch weight conversions**

1. Go to **Product information management** \> **Products** \>
    **Released products**.

2. Select **New**.

3. In the Product number field, enter or select **M7010**.

4. In the Product name field, enter or select **Sugar in 20 lb. bags**.

5. In the **Catch weight** field, select **Yes**.

6. In the **Item model group** field, enter or select FEFO.

7. In the **Item group** field, enter or select AdditiveRM.

8. In the **Storage dimension** group field, enter or select Site.

9. In the **Tracking dimension** group field, enter or select Batch-CP.

10. In the **Inventory unit** field, enter or select **lb**.

11. In the **Purchase unit** field, enter or select **lb**.

12. In the **Sales unit** field, enter or select **lb**.

13. In the **BOM unit** field, enter or select **lb**.

14. Select **OK**.

15. Select **Unit conversions**.

16. Select the **Inter-class conversions** tab.

17. Select **New** to open the drop dialog.

18. Set **Factor** to **20**.

19. In the **To** unit field, enter or select **lb**.

20. In the **From** unit field, enter or select **bag**.

21. Select **OK**.

22. Close the page.

23. In the **Purchase Unit** field, enter or select **bag**.

24. In the **Price** field, enter a number 10000.

25. In the **CW unit** field, enter or select **bag**.

26. Set the **Minimum** quantity to **19**.

27. Set the **Maximum** quantity to **21** and enter **160** for Shelf
    life period in days.

28. Select **Save**.

29. Close the page.

**Create a purchase order for 15 bags of item M7010**

1. Go to **Procurement and sourcing** \> **Purchase orders** \> **All
    purchase orders**.

2. Select **New**.

3. In the **Vendor account** field, enter or select US-111.

    > **Note** If you see a message saying your selected Vendor code is not authorized, kindly ignore it and proceed further.

4. Select **OK**.

5. In the **Item number** field, enter or select **m7010**.

6. Set CW quantity to **15**.

7. On the Action Pane, select **Purchase**

8. Select **Confirm**.

9. Close the page.

**Create a batch number**

1. Go to **Warehouse management \> Setup \> Inventory \> Batches**.

2. Select **New**.

3. In the **Batch number** field, enter or select **GTL002**.

4. In the **Item number** field, enter or select M7010.

5. In the **Manufacturing date** field, enter today's date.

6. Select **Save**.

**Create and post an arrival journal for the purchase order**

1. Go to **Inventory management** \> **Inbound orders** \> **Arrival
    overview**.

2. In the **Arrival overview** profile name field, enter or select
    **Today**.

3. Expand the **Arrival query details** section.

4. Select **No** in the **Production orders** field.

5. Select **No** in the **Transfer orders** field.

6. Select **No** in the **Quarantine orders** field.

7. Select **Update**.

8. In the list, find and select the desired record.

9. Select the **Select for arrival** check box.

10. Select **Start arrival**.

11. Select **Journals**.

12. In the list, find and select the desired record.

13. Select **Journals**.

14. Select **Show arrivals from lines**.

15. Select the **Dimension** tab.

16. Select **Edit**.

17. Select edit icon on Batch number field and select **GTL002**.

18. Select **New**.

19. In the **Batch number** field, enter or select a value.

20. In the **Manufacturing** date field, enter a date.

21. In the **Expiration date** field, enter a date.

22. Select **Save**.

23. Close the page.

24. In the **Batch number** field, enter or select a value.

25. Set **Quantity** to **295**.

26. Select **Save**.

27. Select **Post**.

28. Select **OK**.

29. Post Product Receipt and review Inventory

30. Select **Functions**.

31. Select **Product receipt**.

32. In the **Product receipt** field, enter or select a value.

33. Select **OK**.

### Exercise #20: Use catch weight items in a purchase trade agreement

At company USP2, item number M9401, Cheese, requires a new purchase
trade agreement to be set up for \$175/tray.

The team wants to enter a new demand forecast for 25 trays of cheese to
be sold.

After entering the trade agreement and demand forecast, they want to
enter and confirm a new purchase order for 15 trays.

Finally, master planning should be run and reviewed to determine if
additional trays should be purchased

The team is not sure how to do that. They asked for your help. Can you
help?

You will have to do the following:

- Create a purchase trade agreement

- Create a demand forecast

- Create a purchase order for\
    15 trays of item M9401

- Run net requirements and review the output

#### Steps

**Create a purchase trade agreement**

1. Go to **Product information management** \> **Products** \>
    **Released products**.

2. Use the Quick Filter to filter on the **Item number** field with a
    value of **m9401**.

3. On the Action Pane, select **Purchase**.

4. Select **Create trade agreements**.

5. Select **Edit**.

6. In the **Name** field, enter or select Disc.

7. Select **Lines**.

8. In the **Item relation** field, enter or select **M9401**.

9. In the **Site** field, enter or select **1**.

10. In the Warehouse field, enter or select **11**.

11. Set **Amount in currency** to **175**.

12. Select **Post**.

13. Select **OK**.

14. Close the page.

**Create a demand forecast**

1. On the Action Pane, select **Plan**.

2. Select **Demand forecast**.

3. Select **New**.

4. In the **Model** field, enter or select Current Forecast.

5. In the **Date** field, enter current date.

6. In the **Site** field, enter or select **1**.

7. In the Warehouse field, enter or select **11**.

8. Set **CW quantity** to **25**.

9. Select **Save**.

10. Close the page.

**Create a purchase order for 15 trays of item M9401**

1. Go to **Procurement and sourcing** \> **Purchase orders** \> **All
    purchase orders**.

2. Select **New**.

3. In the **Vendor** account field, enter or select US-111.

4. Select **OK**.

5. In the **Item number** field, enter or select **m9401**.

6. Set **CW quantity** to **15**.

7. Select **Confirm**.

**Run net requirements and review the output**

1. Select **Product and supply**.

2. Select **Net requirements**.

3. Select **Update**.

4. Select **Master planning**.

5. Select **OK**.

### Exercise #21: Create a batch attribute for a potency item

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

    >**Note** In case if Base attribute column is not visible click three
    dots and click Insert columns. Search for b and select Base
    attribute.

4. Click **Update**.

5. In the **Base attribute** field, enter or select **Acidity**.

6. Select **Save**.

### Exercise #22: Modify and activate a copy of a potency item formula

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

4. In the **From date** field, enter current date and click Formula
    version tab on the Action pane.

5. Select **Approval.**

6. In the **Approved by** field, select Glen John.

7. Select **Select**.

8. Select **Yes** in the **Do you also want to approve the formula?**
    field.

9. Select **OK**.

10. Select **Activate**.

### Exercise #23: Set up pricing based on an item's attribute (Bonus)

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

### Exercise #24: Record a potency attribute upon receipt (Bonus)

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

3. Navigate to General Ledger \> Chart of Account \> Structures \>
    Configure account structures.

4. Search for Manufacturing PI P&L

5. Make sure for the main accounts, the "Blank values are allowed"
    option is checked

6. Click on Activate from the Action pane

7. Click on Activate

    > **Note** Once the above steps are completed, please perform steps from "Receive
and enter a batch attribute value to post the order".

8. On the Action Pane, select **Invoice**.

9. Select **Invoice**.

10. In the **Number** field, enter **123**

11. In the **Invoice date** field, enter current date.

12. Select **Update match status**.

13. Select **Post**.

14. On the Purchase order lines . Select **Inventory**.

15. Select **Transactions**.

### Exercise #25: Reporting and balancing batch orders (Bonus)

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

2. Select 24hr and click **Working times.**

3. Select **Compose working times.**

4. In To date field, enter date.

5. In Working time template, select **24hr**. Click **OK**.

6. Close the page once the operation is completed.

7. Close it again till you reach Working time calendars page.

8. Select **8hr** and click **Working times**.

9. Click **Compose working times**.

17. In Working time template field enter **8Hr**. Click **OK**.

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

9. Select a value in **Batch number** field and then click on the same
    batch number

10. Select **New**.

11. In the **Batch number** field, enter or select a value.

12. In the **Manufacturing date** field, enter a date.

13. Select **Save**.

14. Close the page.

15. In the **Batch number** field, select the created batch number.

16. Select **OK**.
