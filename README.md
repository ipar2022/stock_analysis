###stock-analysis

- 
- [x]  Performing analysis to uncover Wall Street trends
- [x]   Macro test message "Hello World" successful
    Dim testMessage As String
    
    
    testMessage = "Hello World!"
    
    
    MsgBox (testMessage)
    
End Sub
Sub DQAnalysis()
    '1) Format the output sheet on the "DQ Analysis" worksheet.
    Worksheets("DQ Analysis").Activate
    
    'Used Range method to name A1'
    Range("A1").Value = "DAQO (Ticker: DQ)"
    
    'Create a header row'
    'Used Cells method to name Rows'
    Cells(3, 1).Value = "Year"
    Cells(3, 2).Value = "Total Daily Volume"
    Cells(3, 3).Value = "Return"
    
    'Renamed A2 DQAnalysis using Range method'
    Range("A2").Value = "DQAnalysis"
    
    'Renamed A2 DQAnalysis using Range Cells method'
     Cells(2, 1).Value = "DQAnalysis"
     
    'Renamed A2 DQAnalysis'
    
End Sub

- DQ traded 107,873,900 shares in 2018.
- Daqo dropped over 63% in 2018.
- Created a new worksheet called "All Stocks Analysis."
- 
- Runtime 2017
![image](https://user-images.githubusercontent.com/113808332/210183853-6ba821a4-c30f-431c-ab74-b9cab5ac2dbe.png)


Runtime 2018
![Runtime 2018](https://user-images.githubusercontent.com/113808332/210183883-c070a84a-24ce-4f0b-ab78-556a6f6545d8.png)



