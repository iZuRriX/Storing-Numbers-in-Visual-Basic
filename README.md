# How to save numbers from a function?

I got the prime numbers from 1 to 100. How do I store them?

My code:

  	Function racunanje()

    Dim p, n, i As Integer

          For n = 1 To 100
              For i = 2 To n - 1
                  If n Mod i = 0 Then
                      p = 0
              Exit For
                  Else
                      p = 1
                  End If
              Next

          If p = 1 Then
              MsgBox ("Prosti brojevi su: " & n)
          End If

          Next

    End Function


    Sub main()

    racunanje

    End Sub


The "main" module is connected to a macro button inside the Excel sheet.
I don't know how to store these numbers and use them later in the code (Working on solving Project Euler 47).
