# Haystack 2.x Core Integrations

This repository contains integrations to extend the capabilities of [Haystack](https://github.com/deepset-ai/haystack) version 2.0 and
onwards. The code in this repo is maintained by [deepset](https://www.deepset.ai), see each integration's `README` file for details around installation, usage and support.

| Package                                                           | Type           | PyPi Package                                                                                                                                 | Status                                                                                                                                                                                                                                                                            |
| ----------------------------------------------------------------- | -------------- | -------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [chroma-haystack](document_stores/chroma/)                        | Document Store | [![PyPI - Version](https://img.shields.io/pypi/v/chroma-haystack.svg)](https://pypi.org/project/chroma-haystack)                             | [![Test / Document Stores / chroma](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/document_stores_chroma.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/document_stores_chroma.yml)                      |
| [elasticsearch-haystack](document_stores/elasticsearch/)          | Document Store | [![PyPI - Version](https://img.shields.io/pypi/v/elasticsearch-haystack.svg)](https://pypi.org/project/elasticsearch-haystack)               | [![Test / Document Stores / elasticsearch](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/document_stores_elasticsearch.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/document_stores_elasticsearch.yml) |
| [instructor-embedders-haystack](components/embedders/instructor-embedders/) | Embedder       | [![PyPI - Version](https://img.shields.io/pypi/v/instructor-embedders-haystack.svg)](https://pypi.org/project/instructor-embedders-haystack) | [![Test / instructor-embedders](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/components_instructor_embedders.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/components_instructor_embedders.yml)        |
| [unstructured-fileconverter-haystack](components/converters/unstructured_fileconverter/) | File converter       | [![PyPI - Version](https://img.shields.io/pypi/v/unstructured-fileconverter-haystack.svg)](https://pypi.org/project/unstructured-fileconverter-haystack) | [![Test / unstructured-fileconverter](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/components_unstructured_fileconverter.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/components_unstructured_fileconverter.yml)

## Contributing

You will need `hatch` to create new projects in this folder. Run `pip install -r requirements.txt` to install it.
