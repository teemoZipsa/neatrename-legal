# ✦ NeatRename Privacy Policy

Last updated: 2026-09-23

> **✦ Quick Synthesis (TL;DR):** NeatRename previews and renames files strictly on your Windows PC. Your files, folder paths, presets, and undo history never leave your device—zero telemetry, zero ads, and zero cloud uploads.

This policy explains what the app reads, what it saves locally, and how your data is protected.

## What the app reads

NeatRename accesses files and folders that you choose through drag and drop, file pickers, folder pickers, or supported Windows launch actions. This can include file names, folder paths, extensions, file sizes, created dates, and modified dates needed to preview, sort, validate, and apply rename operations.

CSV mapping imports are processed from CSV files that you select. Regex replace patterns, template tokens, manual edits, and presets are processed locally to produce the before and after preview.

When a rule needs file metadata, NeatRename can read local Windows properties from selected photos, audio, video, or documents. These can include a title, creator, date taken, dimensions, duration, or other properties used by that rule.

## What the app saves on your PC

NeatRename may store local undo history so that you can reverse rename operations. Undo history can include original file paths, original file names, final file names, operation status, timestamps, and rule summaries.

NeatRename may also store presets, saved workflows, and local app settings that you create, such as rename rules, rule order, source paths, sort preferences, and related UI choices.

In the Microsoft Store MSIX build, local app data is stored in the Windows app local data folder managed for NeatRename. In unpackaged development or fallback scenarios, local data may be stored under:

```
%LOCALAPPDATA%\NeatRename\
```

## Uploads and tracking

NeatRename does not upload, sell, or share your files, file names, folder paths, presets, undo history, settings, CSV mapping files, or regex patterns.

NeatRename does not include advertising, analytics, telemetry, tracking SDKs, cloud sync, or an account system. Rename operations run locally on your device.

## Microsoft Store purchases

If NeatRename offers a paid upgrade through Microsoft Store, Microsoft may process purchase, licensing, billing, and account information according to Microsoft Store policies. NeatRename does not receive your payment card details.

## Your controls

You can delete local undo history and presets from within the app when those controls are available. You can also remove local app data through Windows app settings or by deleting the local data folder used by NeatRename.

Deleting local app data may remove undo history, presets, and settings. It does not change files that have already been renamed on disk.

## Changes to this policy

If NeatRename changes how it handles data, the updated policy will be posted here with a new date.

## Questions

Ask a question in the [NeatRename support issues](https://github.com/teemoZipsa/neatrename-legal/issues/new/choose). Issues are public, so do not include personal file names, paths, or other private details.
