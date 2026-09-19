# SSBI-DATA-VISUALIZATION

## Topics
- Introduction
- Visual Perception
- Visual Cortex and Pre-attentive Processing
- Gestalt Principles Applied to Dashboards
- Cognitive Load and Working Memory Limits

## Introduction
Data visualization goes beyond creating a pie chart and adding a table. Whether it's a movie, a walk, or a dashboard, everything we see stimulates different areas of our brain. If we want to develop professional visualizations, we must stimulate the right areas—that's what separates a random chart from a visualization that truly communicates.

In this repository, I'll explore the neuroscience behind data visualization and how to use it to our advantage.

## Visual Perception
It's the acquisition, interpretation, selection, and organization of information obtained through the senses.

A professional dashboard relies on how the brain processes visual stimuli, not just on organizing data on a screen. "The Scream" by Edvard Munch illustrates this principle: the curved lines that distort the lake and sky guide the viewer's gaze directly to the central figure, communicating anguish before any conscious analysis. Effective dashboards use the same resource—color, shape, and position direct the user's attention to what matters before they need to "read" the data.

<img src="the-scream.jpg" width="400" alt="The Scream by Edvard Munch">

## Visual Cortex and Pre-attentive Processing
The brain processes certain visual properties before conscious attention comes into play—this is called pre-attentive processing. This happens because the primary visual cortex (V1) and associated areas process color, orientation, movement, and size in parallel, in milliseconds, before any cognitive "reading" of the content. That's why, in a scatter plot with 50 blue dots and 1 red dot, you instantly see the red dot—without having to search for it. No conscious effort is spent on this. A professional dashboard uses color, size, and position to exploit this pre-attentive channel—reserving these attributes for the most important data, instead of using them decoratively on everything.

## Gestalt Principles Applied to Dashboards

**Proximity:** Elements that are close together are perceived as a group. **Application:** Related KPIs should be physically close in the layout, not scattered across the screen just because "there's space there."

**Similarity:** Elements with the same color/shape are perceived as belonging to the same category. **Application:** If "revenue" is always blue across all charts in the dashboard, the user generalizes this rule without needing a legend every time.

**Continuity:** The eye follows continuous lines and curves. **Application:** Line charts communicate trends better than bars when the focus is "where is this going," because they directly exploit this principle.

**Closure:** The brain completes incomplete shapes. **Application:** Donut charts work because the brain mentally "closes" the circle—but this is also an argument against using them when reading precision matters more than visual impact.

Each Gestalt principle is, in practice, a shortcut that the brain already uses for free. The work of whoever designs the dashboard is not to fight against these shortcuts.

## Cognitive Load and Working Memory Limits

Human working memory processes few "chunks" of information simultaneously (the exact number is debated, but the central idea—limited capacity—is consensus). Each new visual element (extra color, extra font, extra chart type) consumes part of this limited capacity before the data itself is even interpreted. A dashboard with 6 different chart types, each with its own color palette, forces the user to "restart" the visual decoding process with each chart, even if the data is simple. That's why visual consistency (same palette, same chart type for the same data category) is not an aesthetic choice—it's a direct reduction of cognitive load.
