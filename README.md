# hello-grafana


# sample ddl

```
DROP TABLE backlog_issues;
CREATE TABLE backlog_issues (
    created_at  DATETIME  NOT NULL,
    issue_type VARCHAR(255)  NOT NULL,
    issue_id   VARCHAR(255)  NOT NULL,
    title   VARCHAR(255)  NOT NULL,
    url     VARCHAR(255) NOT NULL,
    status VARCHAR(255) NOT NULL
);
```
