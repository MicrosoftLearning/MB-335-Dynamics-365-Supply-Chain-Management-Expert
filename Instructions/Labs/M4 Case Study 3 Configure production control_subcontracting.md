---
lab:
    title: 'Case study 3 Subcontracting'
    module: 'Module 4 Configure production control'
---

# Module 4 Configure production control

## Case study 3 Subcontracting

### Exercise #1: Set up subcontracting features

The production manager, want to get familiar with the setups before
using the subcontracting features of Microsoft Dynamics 365 Supply Chain
Management.

The company called you as their MFG functional consultant to help the
production manager to better understand the setup.

Can you help?

You will have to do the following:

- Set up the default vendor for a warehouse

- Create a purchase agreement

- Create a work cell for subcontracting (specific to lean
    manufacturing)

- Create an activity-based subcontracting rule (specific to lean
    manufacturing)

- Create and schedule a Kanban for subcontracting (specific to lean
    manufacturing)

- Process and transfer jobs (specific to lean manufacturing)

#### *Steps*

**Set up the default vendor for a warehouse**

1. Go to **Inventory management \> Setup \> Inventory breakdown \>
    Warehouses**.

2. In the list, find and select Warehouse **12-801**.

3. Verify that the **Vendor account** field in the General tab is set
    to **US-801**.

4. Close the page.

**Create a purchase agreement**

1. Go to **Procurement and sourcing \> Purchase agreements \> Purchase
    agreements**.

2. Select **New**.

3. In the **Vendor account** field, enter or select **US-801**.

4. In the **Purchase agreement classification** field, enter or select
    **General purchases**.

5. Expand the **General** section.

6. In the **Expiration date** field, enter a date in future which
    agreements should be expired by.

7. Select **OK**.

8. Expand the **Purchase agreement header** section.

9. In the **Default commitment** field, select **Product value
    commitment**.

10. Select **Lines**. Select **Add line**.

11. In the **Item number** field, enter or select **S0001**.

12. In the **Warehouse** field, enter or select **12-801**.

13. Set **Net amount** to **73570.00**.

14. Select **Add line**.

15. In the **Item number** field, enter or select **S0001**.

16. In the **Warehouse** field, enter or select **12-801**.

17. Set **Net amount** to **50848.00**.

18. In the **Status** field, select **Effective**.

19. Select **Save**.

20. Close all forms.

**Create a work cell for subcontracting**

1. Go to **Organization administration \> Resources \> Resources**.

2. Select **New**.

3. In the **Resource** field, enter or select **GTL-Sub1**.

4. In the **Description** field, enter or select **Subcontractor 1**.

5. In the **Type** field, select **Vendor**.

6. Select **Save**.

7. Close the page.

8. Go to **Organization administration \> Resources \> Resource
    groups**.

9. Select **New**.

10. In the **Resource group** field, enter or select **eBookSub**.

11. In the **Description** field, enter or select **eBook
    subcontractor**.

12. In the **Site** field, enter or select site **1**.

13. In the **Work cell** field, select **Yes**.

14. In the **Input warehouse** field, enter or select **11**.

15. In the **Input location** field, enter or select **11**.

16. In the **Output warehouse** field, enter or select **12-801**.

17. In the **Output location** field, enter or select **801**.

18. In the **Calendars** FastTab, enter or select **Add**.

19. In the **Calendar** field, enter or select **Production**.

20. Collapse the **Calendars** section.

21. In the **Resources** FastTab, select **Add**.

22. In the **Resource** field, enter or select **8821**.

23. Collapse the **Resources** section.

24. In the **Work cell capacity** FastTab, enter or select **Add**.

25. In the **Production flow model** field, enter or select **Mid-Range
    Speaker 2 Flow Model**.

26. In the **Capacity period** field, select **Standard workday**.

27. Set **Average throughput quantity** to **100.00**.

28. In the **Unit** field, enter or select **pcs**.

29. Select **Save**.

30. Close all forms.

**Create Activity based subcontracting rule.**

1. Go to **Production control \> Setup \> Lean production flow \>
    Production flows**.

2. In the list, find and enter or select the **Speaker driver** link to
    get to the details page.

3. Under **Versions** section, enter or select **Add**.

4. Select **OK**.

5. In the list, find and select the new version with a status of
    **Draft**.

6. Select **Activities**.

7. Select **Create new plan activity**.

8. Select **Next**.

9. In the **Name** field, enter or select **GTL-Subcontracting
    activity**.

10. Select **Next**.

11. In the **Work cell** field, enter or select **eBookSub**. You are
    assigning a work cell that is associated with the Vendor.

12. Select **Next**.

13. Select **Next**.

14. In the list, find and select the row for the runtime. Type **1** in
    the **Time** field.

15. In the **Time unit** field, enter or select **hr**.

16. Set **Per quantity** to **10.00**.

17. Select **Next**.

18. Select **Finish**.

19. Select **Create new plan activity**.

20. Select **Next**.

21. In the **Name** field, enter or select **GTL-Transfer to
    subcontractor.**

22. In the **Activity type** field, select **Transfer**.

23. Select **Next**.

24. In the **Replenishing** field, enter or select **eBookSub**.

25. In the **Replenished** field, enter or select **eBookSub**.

26. Select **Next**.

27. Select **Next**.

28. In the list, find and select the row for the runtime. Type **1** in
    the **Time** field.

29. In the **Time unit** field, enter or select **hr**.

30. Set **Per quantity** to **4.00**.

31. Select **Next**.

32. Select **Finish**.

33. In the list, find and select **GTL-Subcontracting activity**.

34. Select **Add successor**.

35. In the **Activity** field, select **GTL-Transfer to subcontractor**.

36. In the **Cycle time ratio** field, enter **1**.

37. Select **OK**.

38. Select **GTL-Transfer to subcontractor** line.

39. Select **Details**

40. Expand **Service terms** FastTab.

41. Select **Add**.

42. In the **Service** field select **S0001**.

43. Select **Next**.

44. In the **Service ratio** field enter or select **1.2**.

45. In the **Service unit** field select or enter **hr**.

46. In the **Service quantity base** field, select **Activity time**.

47. Select **Next**.

48. Select **Finish**.

49. Close the **Activity details** page.

50. Select **GTL-Subcontracting activity**.

51. Select **Details**.

52. Expand **Service terms** FastTab.

53. Select **Add**.

54. In the **Service** field, select **S0001** from the drop down

55. Select **Next**.

56. In the **Service ratio** field, enter or select **1.0**.

57. In the **Service unit** field, select **hr**.

58. In the **Service quantity base** field, select **Activity time**.

59. Select **Next**.

60. Select **Finish**.

61. Close the **Activity details** page.

62. Select **GTL-Transfer to subcontractor**.

63. Select **Add successor**.

64. In the **Activity** field, enter or select **Speaker driver**.

65. In the **Cycle time ratio** field, enter **1**.

66. Select **OK**.

67. Close the **Activities** page.

68. Select version 1 and enter or select **Deactivate.** Select **OK**.

69. Select version 2 and enter or select **Activate.** Select **OK**.

70. Close all forms.

**Create and schedule Kanbans for subcontracting**

1. Go to **Product information management** \> **Lean manufacturing**
    \> **Kanban rules**.

2. Select **New**.

3. In the **First plan activity** field, enter or select
    **GTL-Subcontracting activity**

4. Select the **Multiple activities** check box.

5. In the **Last plan activity** field, enter or select **GTL-Transfer
    to subcontractor**

6. Select **OK**.

7. Select on **Generate flows** and select **OK**

8. In the **Product** field, enter or select **L0001**.

9. Expand the **Quantities** section.

10. Set **Default quantity** to **50.00**.

11. In the **Fixed kanban quantity** field, enter **25**.

12. Expand the Kanban and card Fast Tab

13. Select the **Circulating cards** check box.

14. Change the **Card assignment** to **Automatic**.

15. Select **Save**.

16. Select the **Create cards** button.

17. Clear the **Print new cards** slider to No.

18. Select **Create**.

19. Switch to the **Kanbans** FastTab.

20. Select **Add**.

21. Select **Create**.

22. Go to **Production control \> Kanban \> Kanban job scheduling**.

23. In the **Work cell** field select **eBookSub**.

24. In the list, mark and select the first two rows.

25. Select **Schedule from date** to open the drop dialog.

26. Select **Schedule**.

27. Close all forms.

**Process and transfer jobs**

1. Go to **Production control \> Kanban \> Kanban board for process
    jobs**.

2. In the Work cell field, enter or select **eBookSub**.

3. In the list, mark the selected row.

4. Select **Prepare**.

5. Select **Start**.

6. Select **Complete**.

7. Expand the **Transfer jobs** section.

8. In the list, mark the selected row.

9. Select **Start**.

10. Select **Complete**.

11. Close the page.
