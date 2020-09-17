# Dmitry Shevtsov

**Email:**          dima150754@gmail.com  
**LinkedIn:**       [Link to Profile](https://www.linkedin.com/in/dmitriy-shevtsov-a0b4911a2/)  


### Goals and Aspirations

I have always wanted to be a sought-after specialist,  
create things, services and applications that will be  
useful to people, make their life easier. I also want  
to note the ability to quickly learn from examples,  
punctuality and responsibility.


### Programming Skills 

##### Languages:

* C#
* JavaScript
* Delphi

##### Frameworks:

* React
* NodeJS
* Express


### Code examples

```
const actionsStyles = theme => ({
  root: {
    flexShrink: 0,
    color: theme.palette.text.secondary,
    marginLeft: theme.spacing.unit * 2.5,
   
  },
});

class TablePaginationActions extends React.Component {
    handleFirstPageButtonClick = event => {
        this.props.onChangePage(event, 0);
    };

    handleBackButtonClick = event => {
        this.props.onChangePage(event, this.props.page - 1);
    };

    handleNextButtonClick = event => {
        this.props.onChangePage(event, this.props.page + 1);
    };

    handleLastPageButtonClick = event => {
        this.props.onChangePage(
        event,
        Math.max(0, Math.ceil(this.props.count / this.props.rowsPerPage) - 1),
        );
    };

  render() {
    const { classes, count, page, rowsPerPage, theme } = this.props;

    return (
        <div className={classes.root}>
            <IconButton
            onClick={this.handleFirstPageButtonClick}
            disabled={page === 0}
            aria-label="First Page"
            >
            {theme.direction === 'rtl' ? <LastPageIcon /> : <FirstPageIcon />}
            </IconButton>
            <IconButton
            onClick={this.handleBackButtonClick}
            disabled={page === 0}
            aria-label="Previous Page"
            >
            {theme.direction === 'rtl' ? <KeyboardArrowRight /> : <KeyboardArrowLeft />}
            </IconButton>
            <IconButton
            onClick={this.handleNextButtonClick}
            disabled={page >= Math.ceil(count / rowsPerPage) - 1}
            aria-label="Next Page"
            >
            {theme.direction === 'rtl' ? <KeyboardArrowLeft /> : <KeyboardArrowRight />}
            </IconButton>
            <IconButton
            onClick={this.handleLastPageButtonClick}
            disabled={page >= Math.ceil(count / rowsPerPage) - 1}
            aria-label="Last Page"
            >
            {theme.direction === 'rtl' ? <FirstPageIcon /> : <LastPageIcon />}
            </IconButton>
        </div>
    );
  }
}
```


### Work experience

{ *Place for your advertisement* }


### Education 

Specialized secondary education (2015-2019)  
Qualification - Technician-programmer  

2019 - Present  
Sudent of BSUIR


### English level

Intermediate