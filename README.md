# Parse-C-Layouts
From zero-to-hex-hero: six months of C++, header-layout parsing, and PHP tooling to live-inspect game-database blobs.

# Packed-Blob Inspector 🩺

**What it is** – A tiny utility that decodes a 4-kB
`RoleActivityParam` struct (used in many MMORPG servers) from a MySQL
hex column, shows every field with byte offsets, and lets you patch
individual values safely.
