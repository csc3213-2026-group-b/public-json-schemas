# Public JSON Schemas

## Table of Contents

1. [What is a Schema?](#what-is-a-schema)
2. [What is JSON Schema?](#what-is-json-schema)
3. [How to Use JSON Schema](#how-to-use-json-schema)
4. [More to Know](#more-to-know)

---

## What is a Schema?

A **schema** is a blueprint or rule set that defines how data should be structured. It specifies what fields are allowed, which ones are required, and what type of values they can hold. Schemas are used to ensure data consistency, correctness, and reliability when data is created, shared, or stored.

Think of it as **rules before data**, not after things break.

---

## What is JSON Schema?

**JSON Schema** is a standard for defining and validating the structure of JSON data. It allows developers to describe the expected format of a JSON document, including data types, required properties, and constraints.

JSON Schema is written in JSON itself and is commonly used in APIs, configuration files, and data exchange systems to validate incoming and outgoing JSON data.

---

## How to Use JSON Schema

Just **put `$schema` at the top of your JSON file** and point it to the raw GitHub URL.

```json
{
  "$schema": "https://raw.githubusercontent.com/csc3213-2026-group-b/public-json-schemas/main/path/to/the/schema.json",
  "...": "other fields"
}
```

>NOTE: Change the `/path/to/the/schema.json` with the correct relative path to your schema file in the public GitHub repository.

---

## More to Know

For full specifications, tutorials, and tools, refer to the official documentation:
**[https://json-schema.org](https://json-schema.org)**
