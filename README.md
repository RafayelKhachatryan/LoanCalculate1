# LoanCalculate1
As a lead online financial aggregator , we have to calculate every customer needs with certain accuracy. We used to use a different nuget library for this kind of calculations ExcelFinancialFunctions But this library written F#, it's hard to extend or understand what's happening in it. So we converted base financial functions from F# to C# and pack it with nuget so everbody can use it.

Who?
We are Hesapkurdu R&D Team.You can check our services at Hesapkurdu You can find out who we are & what we are doing at Hesapkurdu Team

Where can I get it?
First, install NuGet. Then install package via package manager console with this command.

PM> Install-Package HkFinancialFunctions
You can also get it from .net cli.

> dotnet add package HkFinancialFunctions
Contributing
Any contributions welcome. Please fork this repository and create a pull request notifying your changes and why.

Financial Dictionary
We are using shortened names of some financial terms.You can find the list here :

fv : Future Value
pv : Present Value
irr : Internal Return Rate
iPmt : Interest Payment
nPer : Number Of Periods
nPv : Net Present Value
pmt : Payment
pPmt : Capital Payment
