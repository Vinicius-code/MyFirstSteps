    Range("C8").Select
      Selection.Value = "Report Title"
   

'Muda a formatação do texto

      With Selection.Font
          .Bold = True    
          .Italic = True
          .Underline = True
          .Color = -16711681
      End With


'Muda o preenchimento da célula    
    
        With Selection.Interior
            .ThemeColor = xlThemeColorAccent1
            .TintAndShade = -0.249977111117893
        End With

    End Sub
