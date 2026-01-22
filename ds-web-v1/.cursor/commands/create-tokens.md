# create-tokens

Generate a complete design token system using the provided inputs.
Steps:
1. Ensure you have understanding of the color scales provided. Ask clarifying questions if needed.
2. Generate a primitive collection using the raw scales provided.
3. Generate a semantic collection mapping brand colors to semantic roles.
4. Generate a component collection including:
    - Surface, text, icon, and border categories
    - All semantic intents
    - All interaction states
    - Explicit light and dark values
5. Generate responsive typography tokens for all text styles.
6. Ensure no component tokens reference primitive or raw values directly.
7. Output JSON files that are compatible with Figma import.
8. Do not invent values, infer meaning, or auto-correct contrast.
9. If required input is missing, pause and request clarification.

Return only the final JSON output.

This command will be available in chat with /create-tokens
