---
title: "How to: Create a Declarative Rule Condition (Legacy) | Microsoft Docs"
ms.date: 11/15/2016
ms.prod: visual-studio-dev14
ms.technology: vs-workflow-designer
ms.topic: "reference"
helpviewer_keywords:
  - "declarative rule conditions"
  - "condition statements, declarative rule conditions"
  - "Rule Condition Editor dialog box"
ms.assetid: 804b6129-c433-408f-a424-46987967730c
caps.latest.revision: 5
author: jillre
ms.author: jillfra
manager: jillfra
---
# How to: Create a Declarative Rule Condition (Legacy)
This topic describes how to declare a rule condition using the legacy [!INCLUDE[wfd1](../includes/wfd1-md.md)] that targets the [!INCLUDE[netfx35_long](../includes/netfx35-long-md.md)] or the [!INCLUDE[vstecwinfx](../includes/vstecwinfx-md.md)].

 A condition statement evaluates to **True** or **False**. A declarative rule condition is a condition statement that is created by using the [Rule Condition Editor Dialog Box (Legacy)](../workflow-designer/rule-condition-editor-dialog-box-legacy.md) and stored as XML with the workflow. It can include predicates that compare workflow state and Boolean algebra that combines multiple predicates.

 Declarative rule conditions are used in the following Windows Workflow Foundation out-of-box activities:

- [ConditionedActivityGroup](https://msdn2.microsoft.com/library/system.workflow.activities.conditionedactivitygroup.aspx)

- [IfElseBranchActivity](https://msdn2.microsoft.com/library/system.workflow.activities.ifelsebranchactivity.aspx)

- [ReplicatorActivity](https://msdn2.microsoft.com/library/system.workflow.activities.replicatoractivity.aspx)

- [WhileActivity](https://msdn2.microsoft.com/library/system.workflow.activities.whileactivity.aspx)

- [SequentialWorkflowActivity](https://msdn2.microsoft.com/library/system.workflow.activities.sequentialworkflowactivity.aspx)

- [StateMachineWorkflowActivity](https://msdn2.microsoft.com/library/system.workflow.activities.statemachineworkflowactivity.aspx)

### To create a declarative rule condition using the Rule Condition Editor

1. In the activity's **Properties** window, click the **Condition** property or **UntilCondition** property, depending on the activity.

2. Select **Declarative Rule Condition** from the list for the property.

3. Expand the **Condition** or **UntilCondition** property.

4. Click the **ConditionName** property.

5. Click the **ConditionName** ellipses **[…]** to open the **Select Condition** dialog box.

6. Click **New Condition** to open the **Rule Condition Editor** dialog box.

7. Type the expression for the condition in the **Condition** text box.

     For information about how to create condition expressions, see [Rule Condition Editor Dialog Box (Legacy)](../workflow-designer/rule-condition-editor-dialog-box-legacy.md).

8. When you are finished creating the condition expression, click **OK** to close the dialog box and create the rule condition with an assigned name.

     The **Select Condition** dialog box opens.

     For information about how to use the **Select Condition** dialog box, see [Select Condition Dialog Box (Legacy)](../workflow-designer/select-condition-dialog-box-legacy.md).

## See Also
 [Legacy Workflow Activities](../workflow-designer/legacy-workflow-activities.md)
 [Using the ConditionedActivityGroup](https://msdn2.microsoft.com/library/bb675237.aspx)
 [Using the IfElseBranchActivity Activity](https://msdn2.microsoft.com/library/bb628465.aspx)
 [Using the Replicator Activity](https://msdn2.microsoft.com/library/bb628544.aspx)
 [Using the While Activity](https://msdn2.microsoft.com/library/bb628552.aspx)
 [Rule Condition Editor Dialog Box (Legacy)](../workflow-designer/rule-condition-editor-dialog-box-legacy.md)
 [Select Condition Dialog Box (Legacy)](../workflow-designer/select-condition-dialog-box-legacy.md)
 [Using Conditions in Workflows](https://msdn2.microsoft.com/library/bb628447.aspx)
