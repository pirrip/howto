### javadoc
**다음의 순서로 작성**
@author (classes and interfaces only, required)
@version (classes and interfaces only, required. See footnote 1)
@param (methods and constructors only)
@return (methods only)
@exception (@throws is a synonym added in Javadoc 1.2)
@see
@since
@serial (or @serialField or @serialData)
@deprecated (see How and When To Deprecate APIs)

```shell
mvn javadoc:javadoc
```
### jautodoc
어떻게 설정할지 아직 결정 못함

### java formatter
`Java > Code Style > Formatter`
Indentation => spaces only - 4
Line Wrapping => Maximum Line Width - 240
Line Wrapping => Never Join Already Wrapped Lines - true (mark)

### java Save Actions
`Java > Editor > Save Actions`
Perform the selected actions on save - check
Format source code - formar all lines (select)

### xml formatter
`XML > XML Files > Editor`
Formatting => Line Width - 120
Formatting => Indent Using Spaces - check
Formatting => Indentation Size - 4
