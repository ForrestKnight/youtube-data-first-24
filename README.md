# YouTube Video Analytics Script

This script utilizes YouTube's Data and Analytics APIs to retrieve video data from a specified YouTube channel and analyze the view count for the first 24 hours after each video's upload.

## Prerequisites

- Python 3.x
- `google-auth-oauthlib` Python library
- `googleapiclient` Python library
- A `client_secret.json` file containing your YouTube API credentials

## Setup

1. Clone this repository:
```
git clone <repo-link>
```
2. Install the necessary Python libraries:
```
pip install --upgrade google-auth-oauthlib google-auth-httplib2 google-api-python-client
```
3. Place your `client_secret.json` in the root of the project directory.

## Usage

1. In the script, replace the `channel_id` variable with your YouTube channel ID.

2. Run the script:
```
python <script-name.py>
```
3. The script will fetch the video data and print out a sorted list of your videos, along with their view counts for the first 24 hours.

Please note that while the script currently analyzes the first 24-hour view count, you can easily modify it to calculate views for the first 30 days or 90 days by uncommenting the respective sections in the code.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.