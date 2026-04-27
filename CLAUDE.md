# Blog

A collection of source code and documentation accompanying blog articles covering topics from C#, ECMAScript 2015, WCF, Azure, and more.

## Tech Stack
- C# (.NET / WCF / Azure)
- JavaScript / ECMAScript 2015
- No build system — static content only

## Project Structure
Content is organised by year and month, with each article having its own folder containing `Code` and `Documentation` subdirectories:
```
Blog/
  2011/ - 2015/       # Year directories
    <MM>/             # Month directories
      <Article>/      # Article folder
        Code/         # Source code samples
        Documentation/
```

## Development
No build process required — browse article folders directly. Each article folder contains standalone code samples.

## Key Notes
- Static content repository — no dependencies to install or servers to run.
- Run `git submodule update --init` after cloning if any submodules are missing.
- Topics: C# 6.0, ECMAScript 2015, WCF, Azure/Kudu CI, XAML, MSMQ scripting.
