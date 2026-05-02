# Graph Report - .  (2026-05-02)

## Corpus Check
- Large corpus: 122 files · ~515,382 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder, or use --no-semantic to run AST-only.

## Summary
- 6436 nodes · 14298 edges · 57 communities detected
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 144 edges (avg confidence: 0.75)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]
- [[_COMMUNITY_Community 22|Community 22]]
- [[_COMMUNITY_Community 23|Community 23]]
- [[_COMMUNITY_Community 24|Community 24]]
- [[_COMMUNITY_Community 25|Community 25]]
- [[_COMMUNITY_Community 26|Community 26]]
- [[_COMMUNITY_Community 27|Community 27]]
- [[_COMMUNITY_Community 28|Community 28]]
- [[_COMMUNITY_Community 29|Community 29]]
- [[_COMMUNITY_Community 30|Community 30]]
- [[_COMMUNITY_Community 31|Community 31]]
- [[_COMMUNITY_Community 32|Community 32]]
- [[_COMMUNITY_Community 33|Community 33]]
- [[_COMMUNITY_Community 34|Community 34]]
- [[_COMMUNITY_Community 35|Community 35]]
- [[_COMMUNITY_Community 36|Community 36]]
- [[_COMMUNITY_Community 37|Community 37]]
- [[_COMMUNITY_Community 38|Community 38]]
- [[_COMMUNITY_Community 39|Community 39]]
- [[_COMMUNITY_Community 40|Community 40]]
- [[_COMMUNITY_Community 41|Community 41]]
- [[_COMMUNITY_Community 42|Community 42]]
- [[_COMMUNITY_Community 43|Community 43]]
- [[_COMMUNITY_Community 44|Community 44]]
- [[_COMMUNITY_Community 46|Community 46]]
- [[_COMMUNITY_Community 48|Community 48]]
- [[_COMMUNITY_Community 53|Community 53]]
- [[_COMMUNITY_Community 54|Community 54]]
- [[_COMMUNITY_Community 56|Community 56]]
- [[_COMMUNITY_Community 57|Community 57]]
- [[_COMMUNITY_Community 58|Community 58]]
- [[_COMMUNITY_Community 59|Community 59]]
- [[_COMMUNITY_Community 60|Community 60]]
- [[_COMMUNITY_Community 62|Community 62]]
- [[_COMMUNITY_Community 63|Community 63]]
- [[_COMMUNITY_Community 64|Community 64]]

## God Nodes (most connected - your core abstractions)
1. `__webpack_require__()` - 177 edges
2. `__webpack_require__()` - 171 edges
3. `AnnotationEditor` - 166 edges
4. `warn()` - 158 edges
5. `AnnotationEditorUIManager` - 143 edges
6. `ConfigNamespace` - 141 edges
7. `__webpack_require__()` - 123 edges
8. `TemplateNamespace` - 115 edges
9. `shadow()` - 102 edges
10. `CanvasGraphics` - 101 edges

## Surprising Connections (you probably didn't know these)
- `guessExtensionFromBuffer()` --calls--> `fileTypeFromBuffer()`  [INFERRED]
  src/conversion/convertToPdf.ts → scripts/browser-compat/stubs/file-type.ts
- `guessFileExtension()` --calls--> `fileTypeFromFile()`  [INFERRED]
  src/conversion/convertToPdf.ts → scripts/browser-compat/stubs/file-type.ts
- `latency_min()` --calls--> `min()`  [INFERRED]
  dataset_eval_utils/src/liteparse_eval/benchmark.py → dataset_eval_utils/src/liteparse_eval/evaluation.py
- `latency_max()` --calls--> `max()`  [INFERRED]
  dataset_eval_utils/src/liteparse_eval/benchmark.py → dataset_eval_utils/src/liteparse_eval/evaluation.py
- `memory_min()` --calls--> `min()`  [INFERRED]
  dataset_eval_utils/src/liteparse_eval/benchmark.py → dataset_eval_utils/src/liteparse_eval/evaluation.py

## Communities

### Community 0 - "Community 0"
Cohesion: 0.0
Nodes (662): 1072(), 1108(), 1148(), 116(), 1291(), 1385(), 1548(), 1625() (+654 more)

### Community 1 - "Community 1"
Cohesion: 0.0
Nodes (81): 1181(), 2731(), 5367(), 7416(), 8454(), 9452(), 9835(), AltText (+73 more)

### Community 2 - "Community 2"
Cohesion: 0.01
Nodes (169): 1181(), 2731(), 3110(), 3650(), 5367(), 7566(), 8454(), 9452() (+161 more)

### Community 3 - "Community 3"
Cohesion: 0.01
Nodes (279): here(), 1072(), 1103(), 1108(), 1148(), 116(), 1291(), 1385() (+271 more)

### Community 4 - "Community 4"
Cohesion: 0.01
Nodes (81): addHex(), Ascii85Stream, AsciiHexStream, AstNode, BaseLocalCache, BasePdfManager, BasePDFStreamRangeReader, BasePDFStreamReader (+73 more)

### Community 5 - "Community 5"
Cohesion: 0.02
Nodes (27): AnnotationElementFactory, applyBoundingBox(), CanvasBBoxTracker, CanvasDependencyTracker, CanvasExtraState, CanvasGraphics, CanvasImagesTracker, CanvasNestedDependencyTracker (+19 more)

### Community 6 - "Community 6"
Cohesion: 0.01
Nodes (23): BasePDFStreamRangeReader, BasePDFStreamReader, BaseShadingPattern, ContourDrawOutline, CurrentPointers, DrawingEditor, DrawingOptions, DrawLayer (+15 more)

### Community 7 - "Community 7"
Cohesion: 0.01
Nodes (133): ABC, Enum, Exception, Benchmark, LatencyMetrics, main(), QAEvalResult, QAResult (+125 more)

### Community 8 - "Community 8"
Cohesion: 0.02
Nodes (83): cleanupConversionFiles(), convertBufferToPdf(), convertImageToPdf(), convertOfficeDocument(), convertToPdf(), executeCommand(), executePowerShell(), findImageMagickCommand() (+75 more)

### Community 9 - "Community 9"
Cohesion: 0.02
Nodes (150): benchmark_provider(), BenchmarkMetrics, get_provider_instance(), latency_max(), latency_min(), main(), memory_max(), memory_min() (+142 more)

### Community 10 - "Community 10"
Cohesion: 0.01
Nodes (4): ConfigNamespace, LZWStream, PostScriptEvaluator, PostScriptStack

### Community 11 - "Community 11"
Cohesion: 0.03
Nodes (42): assert(), BasePDFStream, compileCssFontInfo(), compileFontInfo(), compileSystemFontInfo(), ContextCache, convertBlackAndWhiteToRGBA(), convertRGBToRGBA() (+34 more)

### Community 12 - "Community 12"
Cohesion: 0.03
Nodes (44): applyAssist(), ariaLabel(), BooleanElement, Br, calculateSHA384(), calculateSHA512(), ch(), checkDimensions() (+36 more)

### Community 13 - "Community 13"
Cohesion: 0.03
Nodes (6): BasePDFStream, isRefProxy(), PDFDocumentProxy, PDFPageProxy, RenderTask, WorkerTransport

### Community 14 - "Community 14"
Cohesion: 0.02
Nodes (1): TemplateNamespace

### Community 15 - "Community 15"
Cohesion: 0.03
Nodes (7): 684(), 9835(), Binder, CCITTFaxDecoder, createText(), XFAObject, XFAObjectArray

### Community 16 - "Community 16"
Cohesion: 0.04
Nodes (6): assert(), CssFontInfo, FontFaceObject, FontInfo, PDFNodeStream, SystemFontInfo

### Community 17 - "Community 17"
Cohesion: 0.04
Nodes (12): AlternateCS, CalGrayCS, CalRGBCS, DefaultAppearanceEvaluator, DeviceCmykCS, grayToRGBA(), IccColorSpace, IndexedCS (+4 more)

### Community 18 - "Community 18"
Cohesion: 0.04
Nodes (13): 4576(), 4576(), 4576(), Builder, DatasetReader, DatasetXMLParser, isWhitespaceString(), MetadataParser (+5 more)

### Community 19 - "Community 19"
Cohesion: 0.07
Nodes (8): CFFCompiler, CFFDict, CFFOffsetTracker, CFFParser, CFFPrivateDict, CFFStrings, CFFTopDict, parseIndex()

### Community 20 - "Community 20"
Cohesion: 0.05
Nodes (28): BaseModel, EasyOCRServer, OcrResponse, StatusResponse, MockEasyOCRReader, server(), test_server_ocr_endpoint(), analyze_image_with_claude() (+20 more)

### Community 21 - "Community 21"
Cohesion: 0.05
Nodes (8): CFFFDSelect, Commands, CompiledFont, EvaluatorPreprocessor, lookupCmap(), StateManager, Stipple, Util

### Community 22 - "Community 22"
Cohesion: 0.08
Nodes (1): LocaleSetNamespace

### Community 23 - "Community 23"
Cohesion: 0.08
Nodes (1): GridDebugLogger

### Community 24 - "Community 24"
Cohesion: 0.09
Nodes (7): AstArgument, AstBinaryOperation, AstLiteral, AstMin, AstVariable, AstVariableDefinition, ExpressionBuilderVisitor

### Community 25 - "Community 25"
Cohesion: 0.1
Nodes (6): B, FontSelector, I, layoutText(), P, TextMeasure

### Community 26 - "Community 26"
Cohesion: 0.2
Nodes (2): DOMFilterFactory, isDataScheme()

### Community 27 - "Community 27"
Cohesion: 0.22
Nodes (2): FreeDrawOutliner, FreeHighlightOutliner

### Community 28 - "Community 28"
Cohesion: 0.16
Nodes (3): ColorConverters, makeColorComp(), scaleAndClamp()

### Community 29 - "Community 29"
Cohesion: 0.13
Nodes (1): XhtmlNamespace

### Community 30 - "Community 30"
Cohesion: 0.14
Nodes (1): ConnectionSetNamespace

### Community 31 - "Community 31"
Cohesion: 0.26
Nodes (3): ARCFourCipher, calculateMD5(), CipherTransformFactory

### Community 32 - "Community 32"
Cohesion: 0.26
Nodes (8): computeTextDiff(), getCurrentOutput(), loadDataset(), main(), normalizeForComparison(), findFiles(), main(), processFile()

### Community 33 - "Community 33"
Cohesion: 0.2
Nodes (2): NullOptimizer, QueueOptimizer

### Community 34 - "Community 34"
Cohesion: 0.2
Nodes (9): empty_pdf(), invoice_pdf(), parser(), Shared fixtures for e2e tests., LiteParse instance (auto-detects CLI)., Path to a small single-page invoice PDF., Path to a 2-page PDF., Path to an empty PDF. (+1 more)

### Community 35 - "Community 35"
Cohesion: 0.25
Nodes (1): ToUnicodeMap

### Community 36 - "Community 36"
Cohesion: 0.25
Nodes (1): XFAAttribute

### Community 37 - "Community 37"
Cohesion: 0.25
Nodes (1): PdfiumRenderer

### Community 38 - "Community 38"
Cohesion: 0.38
Nodes (1): SingleIntersector

### Community 39 - "Community 39"
Cohesion: 0.33
Nodes (1): DeviceRgbCS

### Community 40 - "Community 40"
Cohesion: 0.33
Nodes (1): GlyphHeader

### Community 41 - "Community 41"
Cohesion: 0.47
Nodes (1): Intersector

### Community 42 - "Community 42"
Cohesion: 0.4
Nodes (2): AES128Cipher, AES256Cipher

### Community 43 - "Community 43"
Cohesion: 0.4
Nodes (1): CFFIndex

### Community 44 - "Community 44"
Cohesion: 0.4
Nodes (1): HttpOcrEngine

### Community 46 - "Community 46"
Cohesion: 0.83
Nodes (1): ArithmeticDecoder

### Community 48 - "Community 48"
Cohesion: 1.0
Nodes (1): LiteParse Eval - Document parsing evaluation and benchmarking toolkit.

### Community 53 - "Community 53"
Cohesion: 1.0
Nodes (1): Get the CLI path, finding it if not already set.

### Community 54 - "Community 54"
Cohesion: 1.0
Nodes (1): Number of pages in the document.

### Community 56 - "Community 56"
Cohesion: 1.0
Nodes (1): Average latency in seconds.

### Community 57 - "Community 57"
Cohesion: 1.0
Nodes (1): Minimum latency in seconds.

### Community 58 - "Community 58"
Cohesion: 1.0
Nodes (1): Maximum latency in seconds.

### Community 59 - "Community 59"
Cohesion: 1.0
Nodes (1): Standard deviation of latency in seconds.

### Community 60 - "Community 60"
Cohesion: 1.0
Nodes (1): Total latency in seconds.

### Community 62 - "Community 62"
Cohesion: 1.0
Nodes (1): Extract text from a document.          Args:             file_path: Path to the

### Community 63 - "Community 63"
Cohesion: 1.0
Nodes (1): Answer a question about an image.          Args:             image_path: Path to

### Community 64 - "Community 64"
Cohesion: 1.0
Nodes (1): Evaluate whether the predicted answer is correct compared to the expected answer

## Knowledge Gaps
- **122 isolated node(s):** `LiteParse Python wrapper - wraps the Node.js CLI via subprocess.`, `Find the liteparse CLI executable.`, `Parse JSON output from CLI into ParseResult.`, `Build CLI arguments for parse command.`, `Build CLI arguments for batch-parse command.` (+117 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Community 14`** (111 nodes): `TemplateNamespace`, `.appearanceFilter()`, `.arc()`, `.area()`, `.assist()`, `.barcode()`, `.bind()`, `.bindItems()`, `.bookend()`, `.boolean()`, `.border()`, `.break()`, `.breakAfter()`, `.breakBefore()`, `.[$buildXFAObject]()`, `.button()`, `.calculate()`, `.caption()`, `.certificate()`, `.certificates()`, `.checkButton()`, `.choiceList()`, `.color()`, `.comb()`, `.connect()`, `.contentArea()`, `.corner()`, `.date()`, `.dateTime()`, `.dateTimeEdit()`, `.decimal()`, `.defaultUi()`, `.desc()`, `.digestMethod()`, `.digestMethods()`, `.draw()`, `.edge()`, `.encoding()`, `.encodings()`, `.encrypt()`, `.encryptData()`, `.encryption()`, `.encryptionMethod()`, `.encryptionMethods()`, `.event()`, `.exclGroup()`, `.exData()`, `.exObject()`, `.extras()`, `.field()`, `.float()`, `.font()`, `.format()`, `.handler()`, `.hyphenation()`, `.image()`, `.imageEdit()`, `.integer()`, `.issuers()`, `.keep()`, `.keyUsage()`, `.line()`, `.linear()`, `.lockDocument()`, `.manifest()`, `.margin()`, `.mdp()`, `.medium()`, `.message()`, `.numericEdit()`, `.occur()`, `.oid()`, `.oids()`, `.overflow()`, `.pageArea()`, `.pageSet()`, `.para()`, `.passwordEdit()`, `.pattern()`, `.picture()`, `.proto()`, `.radial()`, `.reason()`, `.reasons()`, `.rectangle()`, `.ref()`, `.script()`, `.setProperty()`, `.signature()`, `.signData()`, `.signing()`, `.solid()`, `.speak()`, `.stipple()`, `.subform()`, `.subformSet()`, `.subjectDN()`, `.subjectDNs()`, `.submit()`, `.template()`, `.text()`, `.textEdit()`, `.time()`, `.timeStamp()`, `.toolTip()`, `.traversal()`, `.traverse()`, `.ui()`, `.validate()`, `.value()`, `.variables()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 22`** (26 nodes): `LocaleSetNamespace`, `.[$buildXFAObject]()`, `.calendarSymbols()`, `.currencySymbol()`, `.currencySymbols()`, `.datePattern()`, `.datePatterns()`, `.dateTimeSymbols()`, `.day()`, `.dayNames()`, `.era()`, `.eraNames()`, `.locale()`, `.localeSet()`, `.meridiem()`, `.meridiemNames()`, `.month()`, `.monthNames()`, `.numberPattern()`, `.numberPatterns()`, `.numberSymbol()`, `.numberSymbols()`, `.timePattern()`, `.timePatterns()`, `.typeFace()`, `.typeFaces()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 23`** (26 nodes): `gridDebugLogger.ts`, `createGridDebugLogger()`, `GridDebugLogger`, `.captureRawLines()`, `.captureRender()`, `.debugConfig()`, `.enabled()`, `.flush()`, `.flushSync()`, `.logAnchors()`, `.logBlock()`, `.logBlockContext()`, `.logDuplicateResolution()`, `.logFlowingBlock()`, `.logFlowingLine()`, `.logForwardAnchor()`, `.logForwardAnchorMutation()`, `.logLineComposition()`, `.logRender()`, `.logRenderTrace()`, `.logSnapAssignment()`, `.logStructuredBlock()`, `.matchesBbox()`, `.setPage()`, `.shouldVisualize()`, `.visualizerPages()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 26`** (21 nodes): `.hcmFilter()`, `DOMFilterFactory`, `.addAlphaFilter()`, `.addFilter()`, `.#addGrayConversion()`, `.addHCMFilter()`, `.addHighlightHCMFilter()`, `.#addLuminosityConversion()`, `.addLuminosityFilter()`, `.#addTransferMapAlphaConversion()`, `.#addTransferMapConversion()`, `.#appendFeFunc()`, `.#cache()`, `.constructor()`, `.#createFilter()`, `.#createTables()`, `.#createUrl()`, `.#defs()`, `.destroy()`, `.#hcmCache()`, `isDataScheme()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 27`** (16 nodes): `FreeDrawOutliner`, `.add()`, `.constructor()`, `.#getLastCoords()`, `.#getOutlineEnd()`, `.getOutlines()`, `.#getOutlineStart()`, `.#getOutlineTwoPoints()`, `.isEmpty()`, `.newFreeDrawOutline()`, `.toSVGPath()`, `.#toSVGPathEnd()`, `.#toSVGPathStart()`, `.#toSVGPathTwoPoints()`, `FreeHighlightOutliner`, `.newFreeDrawOutline()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 29`** (15 nodes): `XhtmlNamespace`, `.a()`, `.b()`, `.body()`, `.br()`, `.[$buildXFAObject]()`, `.html()`, `.i()`, `.li()`, `.ol()`, `.p()`, `.span()`, `.sub()`, `.sup()`, `.ul()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 30`** (14 nodes): `ConnectionSetNamespace`, `.[$buildXFAObject]()`, `.connectionSet()`, `.effectiveInputPolicy()`, `.effectiveOutputPolicy()`, `.operation()`, `.rootElement()`, `.soapAction()`, `.soapAddress()`, `.uri()`, `.wsdlAddress()`, `.wsdlConnection()`, `.xmlConnection()`, `.xsdConnection()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 33`** (11 nodes): `NullOptimizer`, `.constructor()`, `.flush()`, `._optimize()`, `.push()`, `.reset()`, `QueueOptimizer`, `.constructor()`, `.flush()`, `._optimize()`, `.reset()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 35`** (8 nodes): `ToUnicodeMap`, `.amend()`, `.charCodeOf()`, `.constructor()`, `.forEach()`, `.get()`, `.has()`, `.length()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 36`** (8 nodes): `XFAAttribute`, `.constructor()`, `.[$getDataValue]()`, `.[$getParent]()`, `.[$isDataValue]()`, `.[$isDescendent]()`, `.[$setValue]()`, `.[$text]()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 37`** (8 nodes): `pdfium-renderer.ts`, `PdfiumRenderer`, `.close()`, `.closeDocument()`, `.extractImageBounds()`, `.init()`, `.loadDocument()`, `.renderPageToBuffer()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 38`** (7 nodes): `SingleIntersector`, `.addExtraChar()`, `.addGlyph()`, `.constructor()`, `.disableExtraChars()`, `.#intersects()`, `.setText()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 39`** (6 nodes): `DeviceRgbCS`, `.constructor()`, `.getOutputLength()`, `.getRgbBuffer()`, `.getRgbItem()`, `.isPassthrough()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 40`** (6 nodes): `GlyphHeader`, `.constructor()`, `.getSize()`, `.parse()`, `.scale()`, `.write()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 41`** (6 nodes): `Intersector`, `.addExtraChar()`, `.addGlyph()`, `.constructor()`, `.#getGridIndex()`, `.setText()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 42`** (6 nodes): `AES128Cipher`, `.constructor()`, `._expandKey()`, `AES256Cipher`, `.constructor()`, `._expandKey()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 43`** (5 nodes): `CFFIndex`, `.add()`, `.count()`, `.get()`, `.set()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 44`** (5 nodes): `http-simple.ts`, `HttpOcrEngine`, `.constructor()`, `.recognize()`, `.recognizeBatch()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 46`** (4 nodes): `ArithmeticDecoder`, `.byteIn()`, `.constructor()`, `.readBit()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 48`** (2 nodes): `__init__.py`, `LiteParse Eval - Document parsing evaluation and benchmarking toolkit.`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 53`** (1 nodes): `Get the CLI path, finding it if not already set.`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 54`** (1 nodes): `Number of pages in the document.`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 56`** (1 nodes): `Average latency in seconds.`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 57`** (1 nodes): `Minimum latency in seconds.`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 58`** (1 nodes): `Maximum latency in seconds.`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 59`** (1 nodes): `Standard deviation of latency in seconds.`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 60`** (1 nodes): `Total latency in seconds.`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 62`** (1 nodes): `Extract text from a document.          Args:             file_path: Path to the`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 63`** (1 nodes): `Answer a question about an image.          Args:             image_path: Path to`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 64`** (1 nodes): `Evaluate whether the predicted answer is correct compared to the expected answer`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `numberToString()` connect `Community 2` to `Community 0`, `Community 9`, `Community 3`?**
  _High betweenness centrality (0.226) - this node is a cross-community bridge._
- **Why does `3110()` connect `Community 3` to `Community 9`, `Community 2`?**
  _High betweenness centrality (0.103) - this node is a cross-community bridge._
- **Why does `456()` connect `Community 3` to `Community 2`?**
  _High betweenness centrality (0.102) - this node is a cross-community bridge._
- **What connects `LiteParse Python wrapper - wraps the Node.js CLI via subprocess.`, `Find the liteparse CLI executable.`, `Parse JSON output from CLI into ParseResult.` to the rest of the system?**
  _122 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.0 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.0 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.01 - nodes in this community are weakly interconnected._