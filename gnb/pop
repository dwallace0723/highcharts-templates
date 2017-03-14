Highcharts.chart('gross-new-business-pop-container', {

  chart: {
    borderRadius: 5,
    spacingTop: 15,
    backgroundColor: 'rgba(255, 255, 255, 0.1)'
  },

  credits: {
    enabled: false
  },

  exporting: {
    enabled: false
  },

  title: {
    text: 'Gross New Subscriptions QoQ',
    align: 'Left',
    style: {
      fontSize: '13px',
      fontWeight: 'bold'
    }
  },

  yAxis: {
    title: {
      text: 'Cumulative Gross New Subscriptions',
      style: {
        fontWeight: 'bold'
      }
    },
    labels: {
      format: '{value:,.0f}'
    }
  },

  xAxis: {
    title: {
      text: 'Day of Quarter',
      style: {
        fontWeight: 'bold'
      }
    }
  },

  plotOptions: {
    series: {
      color: '#1f8ded',
      marker: {
        enabled: false
      },
      pointStart: 1,
      pointInterval: 1
    }
  },

  tooltip: {
    borderRadius: 20
  },

  legend: {
    enabled: true
  },

  series: [{
    name: 'Sales Subscriptions: Previous Quarter',
    data: gns_so_pp,
    color: 'rgba(230,82,90,0.5)'
  }, {
    name: 'Sales Subscriptions: Current Quarter',
    data: gns_so_cp,
    color: '#e6525a'
  },{
    name: 'Self Serve Subscriptions: Previous Quarter',
    data: gns_ss_pp,
    color: 'rgba(126,97,234,0.5)'
  }, {
    name: 'Self Serve Subscriptions: Current Quarter',
    data: gns_ss_cp,
    color: '#7e61ea'
  }]
});
