---
title: CSS cascading and inheritance
slug: Web/CSS/CSS_cascade
page-type: css-module
spec-urls:
  - https://drafts.csswg.org/css-cascade/
  - https://drafts.csswg.org/css-cascade-5/
  - https://drafts.csswg.org/css-cascade-6/
---

{{CSSRef}}

The **CSS cascading and inheritance** module defines the rules for assigning values to properties by way of cascading and inheritance. This module specifies the rules for finding the specified value for all properties on all elements.

One of the fundamental design principles of CSS is cascading of rules. It allows several style sheets to influence the presentation of a document. CSS property-value declarations define how a document is rendered. Multiple declarations may set different values for the same element and property combination, but only one value can be applied to any CSS property. The CSS cascade module defines how these conflicts are resolved.

The opposite also occurs. Sometimes there are no declarations defining the value of a property. The CSS cascade module defines how these missing values should be set via inheritance or from the property's initial value.

> [!NOTE]
> The rules for finding the specified values in the page context and its margin boxes are described in the [CSS page module](/en-US/docs/Web/CSS/CSS_paged_media).

## Reference

### Properties

- {{cssxref("all")}}

### At-rules

- {{cssxref("@import")}}
- {{cssxref("@layer")}}

### Keywords

- {{cssxref("initial")}}
- {{cssxref("inherit")}}
- {{cssxref("revert")}}
- {{cssxref("revert-layer")}}
- {{cssxref("unset")}}
- {{cssxref("important", "!important")}} flag

### Interfaces

- {{DOMXRef("CSSLayerBlockRule")}}
- {{DOMXRef("CSSGroupingRule")}}
- {{DOMXRef("CSSLayerStatementRule")}}
- {{DOMXRef("CSSRule")}}

### Key concepts and definitions

- [specificity](/en-US/docs/Web/CSS/CSS_cascade/Specificity)
- [Cascade origin and importance](/en-US/docs/Web/CSS/CSS_cascade/Cascade)
- [Values](/en-US/docs/Web/CSS/Value_definition_syntax)
  - [actual value](/en-US/docs/Web/CSS/actual_value)
  - [computed value](/en-US/docs/Web/CSS/computed_value)
  - [initial value](/en-US/docs/Web/CSS/initial_value)
  - [resolved value](/en-US/docs/Web/CSS/resolved_value)
  - [specified value](/en-US/docs/Web/CSS/specified_value)
  - [used value](/en-US/docs/Web/CSS/used_value)
- [Origin types](/en-US/docs/Web/CSS/CSS_cascade/Cascade#origin_types)
  - [user-agent origin](/en-US/docs/Web/CSS/CSS_cascade/Cascade#user-agent_stylesheets)
  - [author origin](/en-US/docs/Web/CSS/CSS_cascade/Cascade#author_stylesheets)
  - [user origin](/en-US/docs/Web/CSS/CSS_cascade/Cascade#user_stylesheets)
- [Declaring layers](/en-US/docs/Web/CSS/@import#importing_css_rules_into_a_cascade_layer)
  - [named layer](/en-US/docs/Learn_web_development/Core/Styling_basics/Cascade_layers#the_layer_statement_at-rule_for_named_layers)
  - [anonymous layer](/en-US/docs/Learn_web_development/Core/Styling_basics/Cascade_layers#the_layer_block_at-rule_for_named_and_anonymous_layers)
- Glossary: {{glossary("style origin")}}

## Guides

- [Introducing the CSS Cascade](/en-US/docs/Web/CSS/CSS_cascade/Cascade)

  - : Guide to the cascade algorithm that defines how user agents combine property values originating from different sources.

- [Learn: Handling conflicts](/en-US/docs/Learn_web_development/Core/Styling_basics/Handling_conflicts)

  - : The most fundamental concepts of CSS — the cascade, specificity, and inheritance — which control how CSS is applied to HTML and how conflicts are resolved.

- [Learn: Cascade layers](/en-US/docs/Learn_web_development/Core/Styling_basics/Cascade_layers)

  - : Introduction to [cascade layers](/en-US/docs/Web/CSS/@layer), a more advanced feature that builds on the fundamental concepts of the [CSS cascade](/en-US/docs/Web/CSS/CSS_cascade/Cascade) and [CSS specificity](/en-US/docs/Web/CSS/CSS_cascade/Specificity).

- [CSS inheritance](/en-US/docs/Web/CSS/Inheritance)
  - : A guide to CSS inheritance.

## Related concepts

- [Element-attached styles](/en-US/docs/Web/HTML/Global_attributes/style)
- [Inline styles and the cascade](/en-US/docs/Web/CSS/CSS_cascade/Cascade#inline_styles)
- [Conditional rules for @imports](/en-US/docs/Web/CSS/@import#importing_css_rules_conditional_on_media_queries)

## Specifications

{{Specifications}}

## See also

- [CSS selectors module](/en-US/docs/Web/CSS/CSS_selectors)
- [CSS pseudo-elements module](/en-US/docs/Web/CSS/CSS_pseudo-elements)
- [CSS paged media module](/en-US/docs/Web/CSS/CSS_paged_media)
- [CSS conditional rules module](/en-US/docs/Web/CSS/CSS_conditional_rules)
- [CSS nesting module](/en-US/docs/Web/CSS/CSS_nesting)
- [Shorthand properties](/en-US/docs/Web/CSS/Shorthand_properties)
