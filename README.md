# Handling-Duplicate-Data-in-Python

Hi Again, 

I know the last task around finding inconsistent text was a bit tricky. This should be more straightforward !

Can you check the same file for duplicate data and resolve any issues?

Thanks !

Alan

## Key Objectives

- Find any duplicate data
- Deal with the duplicate data

## Key notes

You can find and fix duplicate data issue by using:
- find duplicate rows in the DataFrame and returns a Boolean Series

  data_frame.duplicated()
- return all duplicate rows

  data_frame[data_frame.duplicated(keep=False)]
- Removes duplicate rows from the DataFrame and Modifies the original DataFrame in place

  data_frame.drop_duplicates(inplace = True)
