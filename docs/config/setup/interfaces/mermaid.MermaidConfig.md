> **Warning**
>
> ## THIS IS AN AUTOGENERATED FILE. DO NOT EDIT.
>
> ## Please edit the corresponding file in [/packages/mermaid/src/docs/config/setup/interfaces/mermaid.MermaidConfig.md](../../../../packages/mermaid/src/docs/config/setup/interfaces/mermaid.MermaidConfig.md).

# Interface: MermaidConfig

[mermaid](../modules/mermaid.md).MermaidConfig

## Properties

### altFontFamily

• `Optional` **altFontFamily**: `string`

#### Defined in

[packages/mermaid/src/config.type.ts:112](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L112)

---

### arrowMarkerAbsolute

• `Optional` **arrowMarkerAbsolute**: `boolean`

Controls whether or arrow markers in html code are absolute paths or anchors.
This matters if you are using base tag settings.

#### Defined in

[packages/mermaid/src/config.type.ts:131](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L131)

---

### block

• `Optional` **block**: `BlockDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:189](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L189)

---

### c4

• `Optional` **c4**: `C4DiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:186](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L186)

---

### class

• `Optional` **class**: `ClassDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:177](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L177)

---

### darkMode

• `Optional` **darkMode**: `boolean`

#### Defined in

[packages/mermaid/src/config.type.ts:103](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L103)

---

### deterministicIDSeed

• `Optional` **deterministicIDSeed**: `string`

This option is the optional seed for deterministic ids.
If set to `undefined` but deterministicIds is `true`, a simple number iterator is used.
You can set this attribute to base the seed on a static string.

#### Defined in

[packages/mermaid/src/config.type.ts:171](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L171)

---

### deterministicIds

• `Optional` **deterministicIds**: `boolean`

This option controls if the generated ids of nodes in the SVG are
generated randomly or based on a seed.
If set to `false`, the IDs are generated based on the current date and
thus are not deterministic. This is the default behavior.

This matters if your files are checked into source control e.g. git and
should not change unless content is changed.

#### Defined in

[packages/mermaid/src/config.type.ts:164](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L164)

---

### dompurifyConfig

• `Optional` **dompurifyConfig**: `Config`

#### Defined in

[packages/mermaid/src/config.type.ts:190](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L190)

---

### elk

• `Optional` **elk**: `Object`

#### Type declaration

| Name                     | Type                                                                          | Description                                                                                                                                               |
| :----------------------- | :---------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `mergeEdges?`            | `boolean`                                                                     | Elk specific option that allows edges to share path where it convenient. It can make for pretty diagrams but can also make it harder to read the diagram. |
| `nodePlacementStrategy?` | `"SIMPLE"` \| `"NETWORK_SIMPLEX"` \| `"LINEAR_SEGMENTS"` \| `"BRANDES_KOEPF"` | Elk specific option affecting how nodes are placed.                                                                                                       |

#### Defined in

[packages/mermaid/src/config.type.ts:91](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L91)

---

### er

• `Optional` **er**: `ErDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:179](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L179)

---

### flowchart

• `Optional` **flowchart**: `FlowchartDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:172](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L172)

---

### fontFamily

• `Optional` **fontFamily**: `string`

Specifies the font to be used in the rendered diagrams.
Can be any possible CSS `font-family`.
See <https://developer.mozilla.org/en-US/docs/Web/CSS/font-family>

#### Defined in

[packages/mermaid/src/config.type.ts:111](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L111)

---

### fontSize

• `Optional` **fontSize**: `number`

#### Defined in

[packages/mermaid/src/config.type.ts:192](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L192)

---

### forceLegacyMathML

• `Optional` **forceLegacyMathML**: `boolean`

This option forces Mermaid to rely on KaTeX's own stylesheet for rendering MathML. Due to differences between OS
fonts and browser's MathML implementation, this option is recommended if consistent rendering is important.
If set to true, ignores legacyMathML.

#### Defined in

[packages/mermaid/src/config.type.ts:153](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L153)

---

### gantt

• `Optional` **gantt**: `GanttDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:174](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L174)

---

### gitGraph

• `Optional` **gitGraph**: `GitGraphDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:185](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L185)

---

### handDrawnSeed

• `Optional` **handDrawnSeed**: `number`

Defines the seed to be used when using handDrawn look. This is important for the automated tests as they will always find differences without the seed. The default value is 0 which gives a random seed.

#### Defined in

[packages/mermaid/src/config.type.ts:76](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L76)

---

### htmlLabels

• `Optional` **htmlLabels**: `boolean`

#### Defined in

[packages/mermaid/src/config.type.ts:104](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L104)

---

### journey

• `Optional` **journey**: `JourneyDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:175](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L175)

---

### layout

• `Optional` **layout**: `string`

Defines which layout algorithm to use for rendering the diagram.

#### Defined in

[packages/mermaid/src/config.type.ts:81](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L81)

---

### legacyMathML

• `Optional` **legacyMathML**: `boolean`

This option specifies if Mermaid can expect the dependent to include KaTeX stylesheets for browsers
without their own MathML implementation. If this option is disabled and MathML is not supported, the math
equations are replaced with a warning. If this option is enabled and MathML is not supported, Mermaid will
fall back to legacy rendering for KaTeX.

#### Defined in

[packages/mermaid/src/config.type.ts:146](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L146)

---

### logLevel

• `Optional` **logLevel**: `0` | `2` | `1` | `"trace"` | `"debug"` | `"info"` | `"warn"` | `"error"` | `"fatal"` | `3` | `4` | `5`

This option decides the amount of logging to be used by mermaid.

#### Defined in

[packages/mermaid/src/config.type.ts:117](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L117)

---

### look

• `Optional` **look**: `"classic"` | `"handDrawn"`

Defines which main look to use for the diagram.

#### Defined in

[packages/mermaid/src/config.type.ts:71](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L71)

---

### markdownAutoWrap

• `Optional` **markdownAutoWrap**: `boolean`

#### Defined in

[packages/mermaid/src/config.type.ts:193](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L193)

---

### maxEdges

• `Optional` **maxEdges**: `number`

Defines the maximum number of edges that can be drawn in a graph.

#### Defined in

[packages/mermaid/src/config.type.ts:90](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L90)

---

### maxTextSize

• `Optional` **maxTextSize**: `number`

The maximum allowed size of the users text diagram

#### Defined in

[packages/mermaid/src/config.type.ts:85](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L85)

---

### mindmap

• `Optional` **mindmap**: `MindmapDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:184](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L184)

---

### packet

• `Optional` **packet**: `PacketDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:188](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L188)

---

### pie

• `Optional` **pie**: `PieDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:180](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L180)

---

### quadrantChart

• `Optional` **quadrantChart**: `QuadrantChartConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:181](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L181)

---

### requirement

• `Optional` **requirement**: `RequirementDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:183](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L183)

---

### sankey

• `Optional` **sankey**: `SankeyDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:187](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L187)

---

### secure

• `Optional` **secure**: `string`\[]

This option controls which `currentConfig` keys are considered secure and
can only be changed via call to `mermaid.initialize`.
This prevents malicious graph directives from overriding a site's default security.

#### Defined in

[packages/mermaid/src/config.type.ts:138](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L138)

---

### securityLevel

• `Optional` **securityLevel**: `"strict"` | `"loose"` | `"antiscript"` | `"sandbox"`

Level of trust for parsed diagram

#### Defined in

[packages/mermaid/src/config.type.ts:121](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L121)

---

### sequence

• `Optional` **sequence**: `SequenceDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:173](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L173)

---

### startOnLoad

• `Optional` **startOnLoad**: `boolean`

Dictates whether mermaid starts on Page load

#### Defined in

[packages/mermaid/src/config.type.ts:125](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L125)

---

### state

• `Optional` **state**: `StateDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:178](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L178)

---

### suppressErrorRendering

• `Optional` **suppressErrorRendering**: `boolean`

Suppresses inserting 'Syntax error' diagram in the DOM.
This is useful when you want to control how to handle syntax errors in your application.

#### Defined in

[packages/mermaid/src/config.type.ts:199](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L199)

---

### theme

• `Optional` **theme**: `"default"` | `"base"` | `"dark"` | `"forest"` | `"neutral"` | `"null"`

Theme, the CSS style sheet.
You may also use `themeCSS` to override this value.

#### Defined in

[packages/mermaid/src/config.type.ts:64](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L64)

---

### themeCSS

• `Optional` **themeCSS**: `string`

#### Defined in

[packages/mermaid/src/config.type.ts:66](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L66)

---

### themeVariables

• `Optional` **themeVariables**: `any`

#### Defined in

[packages/mermaid/src/config.type.ts:65](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L65)

---

### timeline

• `Optional` **timeline**: `TimelineDiagramConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:176](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L176)

---

### wrap

• `Optional` **wrap**: `boolean`

#### Defined in

[packages/mermaid/src/config.type.ts:191](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L191)

---

### xyChart

• `Optional` **xyChart**: `XYChartConfig`

#### Defined in

[packages/mermaid/src/config.type.ts:182](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/config.type.ts#L182)