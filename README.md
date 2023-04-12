# README

## Setup

<p style="text-align: justify"><strong>Before running the code</strong>, you will need to ensure that you have the necessary packages installed. These include <strong>pandas</strong>, <strong>numpy</strong>, <strong>requests</strong>, and <strong>sentence-transformers</strong>. You can install these packages using pip, e.g. <code>pip install pandas</code>.</p>

<p style="text-align: justify">You will also need to obtain a Hugging Face API token and input it in the code where specified.</p>

## Functionality

<p style="text-align: justify">The code reads text from a file and splits it into paragraphs using regular expressions. The resulting paragraphs are written to a CSV file with a single column 'text'. This CSV file is then read into a pandas DataFrame and split into smaller chunks for processing. </p>

<p style="text-align: justify">The <strong>generate_embeddings</strong> function takes a list of texts as input and generates sentence embeddings for each of them using the specified Hugging Face model. The resulting embeddings are returned as a JSON object.</p>

<p style="text-align: justify">The resulting sentence embeddings are then added as a new column to the DataFrame, and the DataFrame is saved in the Parquet file format.</p>

<p style="text-align: justify"><strong>Finally</strong>, the code demonstrates how to generate embeddings for a single input sentence using the <strong>generate_embeddings</strong> function.</p>

<p style="text-align: justify"><strong>Note:</strong> Make sure to input your file paths and Hugging Face API token before running the code.</p>

## Usage

<p style="text-align: justify">To use this code, you can clone the repository and run it on your local machine. Before running the code, make sure to input your file paths and Hugging Face API token where specified. </p>
