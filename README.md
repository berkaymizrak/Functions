# Functions

Many of the functions are blended from the internet and brought together to make it useful. Some of them belongs to me.

<hr>

## File

#### Folder

* **create_folder:** Send name of folder and create it safely.

* **windows_folder_name:** Send name of folder and receive correct format of name.

#### Save & Read

* **save_dict_with_pprint_pformat** and **json_dump:** Save dictionary in nice view to a txt file.

* **dump_data** and **read_dumped_data:** can be used for list or dict.

* **save_records_list** and **read_records_to_list:** can save and read list. You can use these to identify automated programs location. Usage given in code file.

* **save_records_data** and **read_records_data_to_dict:** save and read list data like dict. It can be used for crawl apps to save all dict data fast and more readable than json data.

* **write_ok_and_false_proxy:** Proxy app uses this to read old proxies and save new proxies.

* **find_file:** Send name of the file and it will find correct file name in the path with capital & lower characters.

* **excel_read_to_dict** and **excel_create:** Read and save excel easily with dictionary format.

<hr>

## Connect

* **connect_api:** Tries to get json pages a few times.

* **check_run:** Checks a specific API value and if it is not True, wait untill it gets True.

* **send_email:** Normal smtp mail sender.

* **get_proxy:** Proxy app uses it to fetch updated proxies.

* **internet_connection:** Checks internet connection in apps to continue work.

<hr>

## Progress

* **exit_app:** Show errors in apps easily in nice view.

* **sound_notify:** Send sound notification.

* **speech_text:** Talk given word.

* **progress:** Show progress of working in percentage and nice view.

* **time_definition:** Time to string [day, hour, second etc.]

* **count_down:** Count down from the given number.

* **count_forward:** Count from 0 in the while untill while finished.

<hr>

## String

* **timestamp_def:** Bring date and hour mostly for files to save with date.

* **upper_string, lower_string, title_string:** Function for Turkish characters.

* **replace_last_occurrence:** Replace last character matched in string.

* **date_number_to_date:** Convert number format of date to normal date format.

* **float_to_integer:** If input decimal is 0, returns integer. Otherwise returns float.

<hr>

## Selenium

* **_append_run_path, source_path:** Add path for pyinstaller to create execution well.

* **scroll_down, scroll_up:** Scroll untill end of the page.

* **move_to_element:** Move to element given xpath.

* **check_page:** Go to the link and check the xpath given if element present on the page.

* **turn_off_all_alerts:** Accept or decline popups.

* **captcha_finder:** If captcha in page.

* **captcha_solve:** Solve reCAPTCHA by API.

## Requirements

```
pip install -r requirements.txt
```

