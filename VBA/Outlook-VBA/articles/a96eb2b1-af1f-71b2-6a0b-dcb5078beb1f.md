
# NavigationGroup Object (Outlook)

Represents a navigation group displayed by a navigation module in the Navigation Pane.


## Remarks

Use the  **[Item](a6521179-fa65-b5af-629a-458a852a29b4.md)** method to retrieve a **NavigationGroup** object from the **[NavigationGroups](07206203-36a9-7467-3a89-24fa2a7c2b1f.md)** collection of a parent navigation module, such as a **[MailModule](df20efe5-be5c-952d-c6b7-20c20a83fda0.md)** object. Use the **[Create](5f2bdcfc-4748-4170-7214-bcadc9e3dc36.md)** method of the **NavigationGroups** collection to create a new **NavigationGroup** object.

Use the  **[GroupType](98cad024-903c-35a1-2e30-a0f96a74a4b2.md)** property to determine the group type of the navigation group and the **[Position](b6fb7506-e143-97d8-ae36-0812ca8d7355.md)** property to return or set the display position of the navigation group within the Navigation Pane. You can also use the **[Name](ad66ef0a-1348-372a-f98a-d43171856b35.md)** property to return or set the display name of the navigation group within the Navigation Pane.

Use the  **[NavigationFolders](06e58adc-99d7-dd84-4d23-7f845850ff98.md)** property to return a **[NavigationFolders](ecff93b8-0c3f-5f31-5b61-c46d2622d2af.md)** object containing the navigation folders for the specified navigation group.


## Properties



|**Name**|
|:-----|
|[Application](c3b3e72a-4862-8d34-ce56-1eaf8425d463.md)|
|[Class](4df33ac7-7ede-f2c9-3f00-00668c394930.md)|
|[GroupType](98cad024-903c-35a1-2e30-a0f96a74a4b2.md)|
|[Name](ad66ef0a-1348-372a-f98a-d43171856b35.md)|
|[NavigationFolders](06e58adc-99d7-dd84-4d23-7f845850ff98.md)|
|[Parent](c9d43ee0-ae80-d2f7-93ff-d9948d6e04b9.md)|
|[Position](b6fb7506-e143-97d8-ae36-0812ca8d7355.md)|
|[Session](8be45a52-1a91-2b89-567d-051e1a99178c.md)|

## See also


#### Other resources


[Outlook Object Model Reference](http://msdn.microsoft.com/library/73221b13-d8d8-99b8-3394-b95dbbfd5ddc%28Office.15%29.aspx)