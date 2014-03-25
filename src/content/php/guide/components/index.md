<meta>
{
	"title": "Component Guide",
	"subtitle": ""
}
</meta>

A Dashboard Component is what is displayed to the user - a visual representation of the data that powers the component.

To add a component to the dashboard, you need to first, create a component object and add it to the dashboard.

~~~
$chart = new ChartComponent();
// [.. configure component here ..]
$this->addComponent($chart);
~~~

### Component Guides

* {{ linkArticle ('chart_guide')}}
* {{ linkArticle ('table_guide')}}
* {{ linkArticle ('kpi_guide')}}
* {{ linkArticle ('filter_guide')}}
