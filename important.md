- FILE* fptr = fopen(getenv("output path"), "w");
- char* arr_count_endptr;

char* arr_count_str = readline();

int arr_count = strtol(arr_count_str, &arr_count_endptr, 10);
