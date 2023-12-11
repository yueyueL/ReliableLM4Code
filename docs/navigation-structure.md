---
layout: default
title: Navigation Structure
nav_order: 5
---

# Navigation Structure
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

## Main navigation

The main navigation for your Just the Docs site is on the left side of the page on large screens and on the top (behind a tap) on small screens. The main navigation can be structured to accommodate a multi-level menu system (pages with children and grandchildren).

By default, all pages will appear as top level pages in the main nav unless a parent page is defined (see [Pages with Children](#pages-with-children)).

---

## Ordering pages

To specify a page order, you can use the `nav_order` parameter in your pages' YAML front matter.

### Example (ordering pages)
{: .no_toc }

```yaml
---
layout: default
title: Customization
nav_order: 4
---

```

The parameter values determine the order of the top-level pages, and of child pages with the same parent. You can reuse the same parameter values (e.g., integers starting from 1) for the child pages of different parents.

The parameter values can be numbers (integers, floats) and/or strings. Pages with numerical `nav_order` parameters always come before those with string `nav_order` parameters. When you omit `nav_order` parameters, they default to the titles of the pages. If you want to make the page order independent of the page titles, you can set explicit `nav_order` parameters on all pages. All pages with explicit `nav_order` parameters
come before all pages ordered by their `title` values.

By default, all Capital letters come before all lowercase letters; you can add `nav_sort: case_insensitive` in the configuration file to ignore the case. Enclosing strings in (single or double) quotation marks is optional. Numeric values are not enclosed in quotation marks, e.g., `42`, `-1.0`; numbers in quotation marks are lexicographically ordered, so `"10"` comes before `"2"`, for example.

---
