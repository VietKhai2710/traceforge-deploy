# TraceForge

TraceForge is an Excel add-in for financial model review. It includes formula maps, base/delta sheets, and a lightweight Formula Explorer.

Hosted app:

```text
https://vietkhai2710.github.io/traceforge-deploy/
```

Manifest:

```text
https://vietkhai2710.github.io/traceforge-deploy/manifest.xml
```

## Install In Excel

1. Download `manifest.xml` from:

   ```text
   https://vietkhai2710.github.io/traceforge-deploy/manifest.xml
   ```

2. Put `manifest.xml` in a stable folder on your computer, for example:

   ```text
   C:\OfficeAddins
   ```

   Any folder is fine, as long as you do not delete or rename it later.

3. Open Excel.

4. Go to:

   ```text
   File > Options > Trust Center > Trust Center Settings > Trusted Add-in Catalogs
   ```

5. Add the folder that contains `manifest.xml`.

6. Tick:

   ```text
   Show in Menu
   ```

7. Restart Excel.

8. Go to:

   ```text
   Home > Add-ins > More Add-ins > Shared Folder
   ```

9. Select **TraceForge**.

10. The **TraceForge** tab should appear in the Excel ribbon.

## Basic Use

1. Open an Excel workbook.
2. Select a cell that contains a formula.
3. Go to:

   ```text
   TraceForge > Formula > Explore Formula
   ```

4. Use the Formula Explorer tree to inspect formula parts, values, and source locations.
5. Click rows in the tree to select related workbook ranges.

## Troubleshooting

- If **TraceForge** does not appear, restart Excel and check the Shared Folder add-in list again.
- If Excel says the add-in cannot be loaded, download `manifest.xml` again and replace the old copy.
- If your company blocks external add-ins, ask IT to allow this manifest URL:

  ```text
  https://vietkhai2710.github.io/traceforge-deploy/manifest.xml
  ```

