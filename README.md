## Evidencias realizadas
registros de notas

## hoja de vida

aprendimos a realizar una hoja de vida con markdown

[hoja de vida] (https://github.com/Breitner12/Hoja-de-vida.git)

## visual Basic

se aprendio a ponerle el valor a la variable.

<a href="https://ibb.co/phHWY68"><img src="https://i.ibb.co/fD38jV5/visual-basic.png" alt="visual-basic" border="0"></a>

## starUMTL

en starUMTL la variable se usa en un rectangulo.

<a href="https://ibb.co/WfSHBnM"><img src="https://i.ibb.co/hVpg2s4/strauml.png" alt="strauml" border="0"></a>


## algoritmo
´´´

Sub impuestos()
    pagar = Int(InputBox("valor a pagar por impuestos es: "))
     If pagar > 0 And pagar <= 1000 Then
        MsgBox ("su impuesto a pagar es: 0")
     Else
  If pagar > 1.001 And pagar <= 10000 Then
     inpuesto = ((pagar * 0.5) / 100)
     MsgBox ("pagar: " & inpuesto)
  Else
     If pagar > 10001 And pagar <= 100000 Then
        inpuesto = (pagar * 10) / 100
        MsgBox ("pagar: " & inpuesto)
     Else
       If pagar > 100001 And pagar <= 1000000 Then
          inpuesto = (pagar * 15) / 100
          MsgBox ("pagar: " & inpuesto)
       Else
          If pagar > 1000001 And pagar <= 10000000 Then
             inpuesto = (pagar * 20) / 100
             MsgBox ("pagar: " & inpuesto)
          Else
            If pagar > 10000001 Then
               inpuesto = (pagar * 25) / 100
               MsgBox ("pagar: " & inpuesto)
            End If 
      End If
       End If
        End If
      End If
     End If
End Sub

´´´
