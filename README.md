# JSON Merger

<br>English / [简体中文](README_CN.md)<br><br>

A JSON merger that combines two structurally different JSON files by
supplementing missing parts while preserving main values.

## Overview

- Supports merging JSON files with different structures;
- Preserves all values from the main JSON when conflicts occur.

## How to Use

1. Open [JSON Merger](https://leejch.github.io/json_merger/);
2. Paste your `main JSON` in the first input;
3. Paste your `supplemental JSON` in the second input;
4. Click the `Merge` button;
5. The result will appear below, ready to copy.

## Merge Logic

- JSON structures **do not need to match**;
- Identical items are not duplicated;
- If a key exists in both but values differ, the main JSON's value is kept;
- Any missing keys, arrays, or fields in the main JSON are filled from the supplemental one;
- Arrays merge without duplicating items.

## License

Copyright (C) 2025 [leejch](https://github.com/leejch)

This project is licensed under the terms of the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

You are free to use, modify, and distribute this software, provided that the original copyright and license notice are retained and you comply with the terms of the Apache License 2.0.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
