# Categorized Campaign Finance Contributors Data

CalMatters assigned one of 20 classifications to contributors that gave at least $5,000 to the gubernatorial, insurance commissioner and statewide proposition official campaign committees over the 2025-2026 election cycle. The underlying data for this project came from raw state-level campaign contribution records maintained by the California Secretary of State, accessed by using its [Power Search tool](https://powersearch.sos.ca.gov/). 

Each row in the data includes the raw contributor information including name, employer, occupation, city, state and zip code and the industry code and description assigned by CalMatters.

Read our [methodology](https://calmatters.org/show-your-work/2026/11/how-we-classified-nearly-900-million-in-contributions-from-individuals-companies-and-pacs/) for more information on how we classified contributors.

## Data Dictionary

| Column name | Description |
|---|---|
| name | Raw contributor name from the `Contributor Name` field in the Power Search data |
| employer | Raw contributor employer name from the `Contributor Employer` field in the Power Search data|
| occupation | Raw contributor occupation from the `Contributor Occupation` field in the Power Search data |
| city | Raw contributor city from the `Contributor City` field in the Power Search data |
| state | Raw contributor state from the `Contributor State` field in the Power Search data |
| zip | Raw contributor zip code from the `Contributor Zip Code` field in the Power Search data |
| industry code | Industry code assigned by CalMatters |
| industry code description | Description of industry code (see CalMatters Campaign Finance Categories below) |

## CalMatters Campaign Finance Categories

| Industry | Description |
|---|---|
| Agriculture/Livestock | Businesses involved in crop farming, cattle and livestock ranching, poultry and egg production, vineyards, and other support activities for agriculture. |
| Oil and Gas | All businesses tied to oil and gas, including those involved in drilling, refining and distribution companies. |
| Utilities/Infrastructure | Utilities include electric power generation and distribution, natural gas distribution, water, sewage and similar systems and all telecommunications companies. Infrastructure comprises transportation and warehousing companies including airlines, trucking, buses and railroads. Waste management services are also included in this category. |
| Manufacturing | All types of manufacturing, including food and beverage manufacturing, tobacco manufacturers, apparel, chemical and pharmaceutical manufacturers and similar entities. |
| Real Estate/Construction | Real estate companies include offices of real estate agents and brokers, lessors of real estate and property managers. Construction companies include building construction, providing raw materials for construction, land subdivision, highway, street and other civil engineering construction and building contractors. Many companies overlapped: developers who own real estate but also build out properties they own. This category also includes organizations involved in rental and leasing like car, machinery and consumer goods rentals, based on NAICS codes. |
| Professional/Legal | Organizations classified under professional/legal include law offices, accounting firms, tax preparers and those involved in payroll services. This category also includes architectural and engineering related services, consulting and business support services, scientific research and development, advertising, public relations and management and holding companies. |
| Finance/Insurance | Finance-affiliated organizations include banks, credit unions, and organizations involved in financial investment activities. Insurance includes insurance carriers, agencies and brokerages and insurance-related activities such as employee benefit funds. Integrated health systems that are both a health insurer and a care provider (like Kaiser Permanente and Sutter Health) are classified under insurance. |
| Healthcare/Education | Education includes elementary and secondary schools, colleges, universities and professional and trade schools as well as educational support services. Healthcare includes offices of physicians, dentists and other health practitioners, hospitals, nursing care and assisted living facilities. Social services such as community food and housing, emergency relief, child care services, rehab services and libraries also fall into this category. |
| Entertainment, Media and Gambling | Entertainment, media and gambling companies include casinos, motion picture and video industries, sports, leisure, radio and television broadcasting stations, newspapers and publishers and museums and similar institutions. |
| Associations | Business, professional and trade associations. |
| Unions | All unions including public sector unions, trade unions, social services unions and others. |
| Technology | Technology, software and AI companies, including: AI services, software publishers, media streaming and distribution services, social networks, web hosting and data processing. This category is used if the business's primary product is a tech product, even if that product was designed to serve a different industry (e.g. health tech or fintech). |
| Other Industries | Includes organizations involved in food and accommodation as well as organizations involved in retail sales and wholesale trade, nonprofit, philanthropic and religious organizations and businesses that do personal care services or repair and maintenance. |
| Candidates/Political Parties | Candidate committees, political parties and PACs run by a political party or candidate. |
| Government/Public Safety | Public administration, including government offices, law enforcement and peace officers, judicial, ambulance and court services. This category also includes space research, national security and international affairs and defense contractors. |
| Tribes | Native American tribes, including tribal casinos and other tribal gaming operations. |
| Uncategorized | This category includes contributors for which CalMatters could not determine a category and all contributors that gave less than $5,000 to a contest or committee we classified. |
| Major Donors/Megadonors | Individuals who contributed to a campaign and listed that they were retired or did not list a specific employer. This category also includes prominent individuals who may not be linked to one particular industry and family trusts. |
| Small Donors | Contributions of less than $100 to a recipient. This category includes contribution records that are explicitly labeled "Unitemized Contributions" and contributors that donated less than $100 in aggregate to a recipient. The exceptions are unions and associations that pool membership funds for political action. |
| Self-Funding | Funding from candidates who gave to their own campaign. |

## Examples of Use

- CalMatters used the categorized data to compute industry breakdowns for the [gubernatorial](https://calmatters.org/california-voter-guide-2026/governor/#campaign-finance), [insurance commissioner](https://calmatters.org/california-voter-guide-2026/insurance-commissioner/#campaign-finance) and statewide proposition official campaign committees (for example, [Proposition 39](https://calmatters.org/california-voter-guide-2026/proposition-39-voter-id/#proposition-committees), which would have required identification for voting) and published the results on our [Voter Guide](https://calmatters.org/california-voter-guide-2026/). 
- CalMatters reporters also used the categorized data to [report on](https://calmatters.org/economy/technology/2026/10/tech-interests-spend-big-on-california-election/) Big Tech spending in the 2025-2026 election cycle.

## Data Use

While the contents of this repo are shared under an Apache 2.0 license, CalMatters would appreciate any credit or attribution you're willing to give. We're also interested to learn how you used it, so feel free to [send us a message](<mailto:natasha@calmatters.org>) if you do. If you have any questions, feel free to [contact us](<mailto:natasha@calmatters.org>) as well.

CalMatters is a nonpartisan, nonprofit journalism venture committed to explaining how California’s state Capitol works and why it matters.
