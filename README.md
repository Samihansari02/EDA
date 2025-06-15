
# EDA on Diwali Sales

The main objective is to improve customer experience by analyzing sales data and Increase the revenue.


## API Reference

#### pandas.DataFrame.groupby()

```http
  Groups the data in a DataFrame based on one or more columns.

```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `by` | `string` | The column(s) to group by |
| `as_index` | `bool` | Whether to set the group keys as the index of the returned object |
| `sort` | `bool` | Whether to sort the group keys |

#### pandas.DataFrame.sort_values()

```http
  Sorts a DataFrame by the values of one or more columns.
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `ascending`      | `bool` | If True, sort in ascending order; if False, descending |

#### seaborn.barplot()

```http
  Creates a bar plot for categorical data.
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `data`      | `DataFrame, array, or list of arrays` | Data to plot |
| `x`      | `string` |  Name of the column in data to use for x-axis values |
| `y`      | `string` | Name of the column in data to use for y-axis values |
| `hue`      | `string` |Grouping variable for color coding bars |


#### seaborn.set()

```http
  Sets aesthetic parameters for plots globally.
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `context`      | `string` | Plot context (e.g., "paper", "notebook", "talk", "poster") |
| `style`      | `string` | Plot style (e.g., "whitegrid", "darkgrid") |
| `rc`      | `dict` | Dictionary of parameters to set |
| `palette`      | `string` | Color palette |

#### matplotlib.pyplot.figure()

```http
  Creates a new figure for a plot.
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `figsize`      | `tuple of floats` | Specifies the figure size in inches (width, height) |




