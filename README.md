<h1 id="go-introduction">Go Introduction</h1>
<h2 id="what-is-go-">What is Go?</h2>
<ul>
<li>Go language chai cross-platform(junsukai environment ma run huney) ra open source programming language ho.</li>
<li>Go chai ekdam high-performance applications haru banauna lai use hunxa.</li>
<li>Go chai fast, statically typed (yesma chai compilation time ma variable type thaha hunxa), compiled language ho jun le chai dynamically typed(yesma chai run time thahahunxa hunxa) jasto feel garauxa.</li>
<li>Yo language chai google ma Robert Griesemer, Rob Pike, and Ken Thompson in 2007.</li>
<li>Go language ko syntax chai c++ snga ekdam mildo juldo hunxa.</li>
</ul>
<h2 id="what-is-go-used-for-">What is Go Used for?</h2>
<ul>
<li>Web development (server-side)</li>
<li>Network-based programs haru develop garna</li>
<li>Cross Platform app haru develop garna</li>
<li>Cloud-native develop garna lai use hunxa</li>
</ul>
<h2 id="why-go-">Why Go?</h2>
<ul>
<li>Easy to learn</li>
<li>compilation time ra run time fast hunxa</li>
<li>concurrency( performing multiple things out-of-order) support garxa </li>
<li>memory management</li>
<li>different platform ma kaam garxa jastai: Windows, Mac, Linux, Raspberry Pi, etc</li>
</ul>
# Get Started

Go language suru garna lai hamlai duita kura ko jarurat hunxa:
- Text Editor jastai: VS code, Go lang ko code lekhna.
- Ani, compiler jasle chai Go code lai computer le bujne bhasa ma translate garxa.

# Go Install

Tapai le Go ko Installation file yaha paunuhunxa https://go.dev/doc/install 

Install garisakesi install vayo ki vako xaina vanera check garna lai cmd open garnu hoss ani: `go version` lekhnus yesle tapai ko pc or laptop ma install vaye ko go lang ko version dekhauxa.

# Go Syntax

Go language ko file chai following parts ma divide vako hunxa:

- Package declaration
- Import  Package
- Functions
- Statements and expression

yo kura lai bujna aaba ekchin tala ko code lai herun:
```Go
package main
import ("fmt")
func main() {
    fmt.Println("Hello")
}
```
Aaba yeslai part part ma bujaum:

- Line 1 ma hamle `package` keyword define gareko xaum ani mathi ko exmaple ko program `main` package ma belong garxa.

- Line 2 ma `import ("fmt")` xa jasle chai hamilai `fmt` package ma based vako file haru import garna dinxa.

- Line 3 ma chai `func main() {}` xa yo chai main func ho, yo main function ko curly bracket vhitra lekheko code haru execute hunxa.

- Line 4 ma chai `fmt.Println()` function xa junchai fmt package ma based hunxa jasle chai output diney kaam garxa jastai mathi ko code le `Hello` output dinxa.

# Go Compact code

Hamle chai Go lang lai ajhai compactly lekhna milxa
```Go
package main; import ("fmt"); func main() { fmt.Println("Hello");}
```
Yo chai recomendable xaina just information ko lagi matrai ho kina vane yo way ma code lai bujna ekdam complex hunxa.

# Go Comments
- Single line comments ko lagi (`//`) duita forward slashes use garna milxa.
- Multi-line comments ko lagi chai `/*` your comments here `*/`.

# Go Variables

Variables vaneko chai euta container or box ho jun chai value store garna lai use hunxa.




