# Open source file format standard

A standard for open source file formats so applications and people can easily understand how they work.

## What is the OSFF standard?

The OSFF standard is a standard for file formats to make it easier for people to understand how a file format works and how it is structured. This is done by documenting the file format and the key parts of the file format.

## Why?

When a file format is made it is hard to understand how the file works and how its structured because sometimes the file format is not well documented or not documented at all. This makes it hard for people to understand how the file works and makes it harder for developers to make applications that can read and write the file format.

## What should I do to meet the OSFF standard?

To meet the Open Source File Format standard you should document your file format where ever your documentation is and make a section taking about the file format and how it works. In this section you should talk about what the file format is, information about it, magic numbers or strings, how the file is structured, where is is commonly stored and so on.

### Template

Here is a example for one file format:

```markdown
# My example project

This here is your project documentation.

## File format

This file format is used to store XXXX data and is used by XXXX. It is commonly stored at `XXXX`...

### File structure

The XXXX amounts of bytes defines ... at the end of the file there are XXXX bytes that define ... and that do ... this then does ...

### Magic numbers

There are XXXX amount of magic numbers in this file format.

| Magic number   | Description |
| -------------- | ----------- |
| `XXXX`         | XXXX        |
| `XXXX`         | XXXX        |

**NOTE ALL MAGIC NUMBERS ARE IN HEX** <- Don't include this
```

Here is a example for multiple file formats:

```markdown
# My example project

This here is your project documentation.

## File formats

This project has the following file formats:

- [File type 1](#file-type-1)
- [File type 2](#file-type-2)

### File type 1

This file format is used to store XXXX data and is used by XXXX. It is commonly stored at `XXXX` ...

#### File structure

The XXXX amounts of bytes defines ... at the end of the file there are XXXX bytes that define ... and that do ... this then does ...

#### Magic numbers

There are XXXX amount of magic numbers in this file format.

| Magic number   | Description |
| -------------- | ----------- |
| `XXXX`         | XXXX        |
| `XXXX`         | XXXX        |

**NOTE ALL MAGIC NUMBERS ARE IN HEX** <- Don't include this

### File type 2

This file format is used to store XXXX data and is used by XXXX. It is commonly stored at `XXXX`...

#### File structure

The XXXX amounts of bytes defines ... at the end of the file there are XXXX bytes that define ... and that do ... this then does ...

#### Magic numbers

There are XXXX amount of magic numbers in this file format.

| Magic number   | Description |
| -------------- | ----------- |
| `XXXX`         | XXXX        |
| `XXXX`         | XXXX        |

**NOTE ALL MAGIC NUMBERS ARE IN HEX** <- Don't include this
```

## How do I know if a file format meets the OSFF standard?

If you document properly and people can understand how the file format works by reading the documentation then it meets the OSFF standard.

## How do I let people know that my project meets the OSFF standard?

You can add the OSFFS logo (Found at `logos/`) to your project to let people know that your project meets the OSFF standard. You can also add the following texts to your project:

```
This project meets the [Open Source File Format standard](https://www.github.com/lewisevans2007/OSFFS).
```

```
This project is [OSFFS Compliant](https://www.github.com/lewisevans2007/OSFFS).
```

```
[OSFFS Comliant](https://www.github.com/lewisevans2007/OSFFS)
```

