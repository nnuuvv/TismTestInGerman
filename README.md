# TismTestInGerman
Started as the [RAADS-R](https://embrace-autism.com/raads-r/) test, translated to german. Without People taking the test knowing what test they're taking.

Works for any list of questionNr;question;weight;weight;.. provided in a QuestionsAndWeights.csv in the /Data/ folder. <br/>
Since its based on the RAADS-R test the default looks like this:
```
1;Ich bin ein sympathischer Mensch.;0;1;2;3
2;Ich benutze oft Wörter und Phrasen aus Filmen und Fernsehen in Gesprächen.;3;2;1;0
3;Ich bin oft überrascht, wenn andere mir sagen, dass ich unhöflich gewesen bin.;3;2;1;0
```

The amount of weights and answer options can be adjusted, <br/>
by adding more weights and their associated RadioButtonItems at line 25 of /Pages/RAADSR.razor
