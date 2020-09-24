<div align="center">

## Trim, LTrim & RTrim in Javascript


</div>

### Description

These functions have the same functionality as the homonymous ones in VBScript, they remove leading and/or trailing spaces from a given string
 
### More Info
 
Any String

The string inputed less leading and/or trailing spaces


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Walter Staeblein](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/walter-staeblein.md)
**Level**          |Beginner
**User Rating**    |4.3 (17 globes from 4 users)
**Compatibility**  |
**Category**       |[String Manipulation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/string-manipulation__2-60.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/walter-staeblein-trim-ltrim-rtrim-in-javascript__2-3096/archive/master.zip)





### Source Code

```
<script language="javascript">
function jsTrim(TXT)
{
	return TXT.replace(/(^\s+)|(\s+$)/g,"");
}
function jsLTrim(TXT)
{
	return TXT.replace(/(^\s+)/g,"");
}
function jsRTrim(TXT)
{
	return TXT.replace(/(\s+$)/g,"");
}
</script>
```

