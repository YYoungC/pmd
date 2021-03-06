---
title: PMD Release Notes
permalink: pmd_release_notes.html
keywords: changelog, release notes
---

## {{ site.pmd.date }} - {{ site.pmd.version }}

The PMD team is pleased to announce PMD {{ site.pmd.version }}.

This is a {{ site.pmd.release_type }} release.

{% tocmaker is_release_notes_processor %}

### New and noteworthy

### Fixed Issues

*   apex-bestpractices
    *   [#2626](https://github.com/pmd/pmd/issues/2626): \[apex] UnusedLocalVariable - false positive on case insensitivity allowed in Apex
*   java-performance
    *   [#1736](https://github.com/pmd/pmd/issues/1736): \[java] UseStringBufferForStringAppends: False positive if only one concatenation
    *   [#2207](https://github.com/pmd/pmd/issues/2207): \[java] False positive: AvoidInstantiatingObjectsInLoops should not flag objects when assigned to lists/arrays

### API Changes

### External Contributions
*   [#2558](https://github.com/pmd/pmd/pull/2558): \[java] Fix issue #1736 and issue #2207 - [Young Chan](https://github.com/YYoungC)

{% endtocmaker %}

