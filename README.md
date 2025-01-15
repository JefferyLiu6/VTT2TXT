# VTT to Plain Text Converter

A simple script to convert `.vtt` subtitle files into plain text by removing timestamps, numbering, and metadata.

---

## How to Use

1. Update the file paths in the script:
   ```python
   vtt_file = 'path_to_your_file.vtt'  # Input VTT file
   output_file = 'path_to_output_file.txt'  # Output text file
   ```
2. Run the script:
   ```python
   vtt_to_text.py
   ```
3. The plain text will be saved in the specified output file.


## Example

**Input (`42.vtt`):**

```csharp
WEBVTT

1
00:00:00.000 --> 00:00:02.000
This is an example subtitle.

2
00:00:02.500 --> 00:00:04.000
Here is another line.
```

**Output (output42.txt):**

```csharp
This is an example subtitle. Here is another line.
```

---

Enjoy the simplicity! 😊
