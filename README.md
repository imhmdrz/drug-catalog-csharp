# Drug Catalog

A C# data-structures course project for searching drug records, exploring relationships, and calculating prices.

## What it demonstrates

A console application developed for a university data-structures course. It uses lists and hash tables to manage drug and disease records, inspect relationships, calculate a basket price, and apply percentage price increases.

**Stack:** C# · .NET 5 · `List<T>` · `Hashtable` · Text-file datasets

## Getting started

The project targets `net5.0`. Use a compatible .NET SDK and runtime; .NET 5 is an older, unsupported target.

```bash
git clone https://github.com/imhmdrz/drug-catalog-csharp.git
cd drug-catalog-csharp
dotnet run --project proj/proj/proj.csproj
```

At the first prompt, choose **2** to enter dataset paths. Option 1 points to the original developer's Windows directory. Supply the absolute paths to these files in this order:

1. `DS-Final-Project/datasets/drugs.txt`
2. `DS-Final-Project/datasets/diseases.txt`
3. `DS-Final-Project/datasets/alergies.txt`
4. `DS-Final-Project/datasets/effects.txt`

Follow the numbered console menu; choose **7** to finish. Preserve the existing spelling of `alergies.txt` when entering the path.

## Repository guide

| Path | Contents |
| --- | --- |
| `proj/proj/Program.cs` | Data structures and interactive menu |
| `proj/proj/proj.csproj` | .NET project definition |
| `DS-Final-Project/datasets/` | Sample text datasets |
| `DS-Final-Project/Final-Project.pdf` | Course project specification |

This is an educational dataset exercise, not a clinical drug reference.
